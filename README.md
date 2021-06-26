![Cover photo of Colab-ssh](docs/assets/cover.png)

> 🎉 Happy to announce that we now support:
>  - Argo Tunnel (also known as cloudflared)
>  - VSCode direct link with which you can open your VSCode right from the notebook.

# Colab-ssh
#### Connect to Google colab via ssh easily

[![Downloads](https://pepy.tech/badge/colab-ssh/week)](https://pepy.tech/project/colab-ssh/week)
[![Downloads](https://pepy.tech/badge/colab-ssh/month)](https://pepy.tech/project/colab-ssh/month)
[![Downloads](https://pepy.tech/badge/colab-ssh)](https://pepy.tech/project/colab-ssh)

## What is Colab-ssh ?
Colab-ssh is a light-weight library that enables you to connect to a Google Colab virtual machine using an SSH tunnel.

> <details><summary> <b> Can I open the Colab notebook automatically without user interaction ?</b> </summary>No, you still need to open the Google Colab Notebook interface manually in order to setup this tool. Google Colab doesn't have an API yet to automatically run a notebook for you.</details>

> :warning: Colab-ssh supports Google colaboratory notebooks only, using it on other notebooks may lead to unexpected behavior. 

## Getting started

1. Open Google Colab and run this code in one of the code cells
```jupyter
# Install colab_ssh on google colab
!pip install colab_ssh --upgrade

from colab_ssh import launch_ssh_cloudflared
launch_ssh_cloudflared(password="<PUT_YOUR_PASSWORD_HERE>")

```
> Make sure you replace `<PUT_YOUR_PASSWORD_HERE>` with a password of your choice

The output of this snippet will look similar to the following screenshot:
![launch_ssh_cloudflared output](docs/assets/launch_ssh_cloudflared.jpg)



# Sponsor this project :)
If you want to buy me a cup of coffee, feel free to reach me or use the following IBAN (International Bank Account Number):
```
TN5904018104003696876646
```

# Contribution
Start by [opening an issue](https://github.com/WassimBenzarti/colab-ssh) so can start working together to enhance the experience of Google Colab users. We would love to hear your ideas!
