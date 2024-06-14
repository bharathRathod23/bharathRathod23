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

