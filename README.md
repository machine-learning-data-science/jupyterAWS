# jupyterAWS
Here are a few scripts to setup jupyter on your AWS instance

# Setup

1. Run ec2script.sh with the command "bash ec2script.sh"
2. Fill out the password you want to use for your jupyter notebook
3. Fill out the information for your web certificate information (feel free to click enter through each prompt)
4. Run jupyter.sh by typing "bash jupyter.sh"
5. In your web browser navigate to "https://[AWS PUBLIC DNS IPv4 here]:8888". The https is necessary
6. If in chrome you will most likely get a warning that the certificate is not veriified. This is because you just created it. Click advanced and then click the prompt that goes something like "Proceed to https://........:8888 anyways"