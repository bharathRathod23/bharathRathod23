- 👋 Hi, I’m @bharathRathod23


steps to generate ssh key


1) to generate new ssh key
   ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

2) Add SSH Key to SSH Agent

   Start the SSH agent in the background (if not already running):
   eval "$(ssh-agent -s)"

   Add your SSH private key to the SSH agent
   ssh-add ~/.ssh/id_rsa


copy the ssh key and add it to github


3) Verify SSH Key Setup

   ssh -T git@github.com

   You may see a message asking you to confirm the authenticity of the host. Type yes to continue. If everything is set up correctly, you will see a message like:

Hi username! You've successfully authenticated, but GitHub does not provide shell access.



