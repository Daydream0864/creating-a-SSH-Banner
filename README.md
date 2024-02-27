# creating-a-SSH-Banner
# What is a SSH-Banner
- a SSH-Banner pops up everytime you open up or coonecct to a ssh service in a Terminal. A Banner apears in a Terminal. It could be an informative one or just Art in form of ASCI form.

# Creating a SSH-Banner
1. go to the `/etc/issue.net` an use NANO for your editor
2. change what your Message will be.
3. Change directory to `/etc/ssh/sshd_config` and search for the word "Banner" remove the hashtag and put the path in it(`/etc/issue.net`).
4. log in via SSH and you will see your banner in the Terminal.

- Tip: the whole procedure can be donevia SSH.
