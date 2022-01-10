# Chrome-Remote-Desktop-Google-Colab-Instance

## Simple notebook to access "Remote Desktop with GUI of Google Colab Instance"
This script uses chrome remote desktop and xfce desktop environment to provide desktop remote with GUI for Google colab notebook.

<a href="https://colab.research.google.com/drive/11A5j4TfGPOoMxjpVI8FPsKtGWTae8I8J?usp=sharing" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Tutorial
1. Click the badge which says 'Open in Colab'.
2. change the username and password in first cell to your requirement.
3. Run the first cell to create new user.
4. Click on http://remotedesktop.google.com/headless to get a debian linux oauth code for CRD
5. copy the outh code and paste it into CRP input form.
6. Enter 6 or more digits Pin in the Pin input form.
7. Run the second cell to add goole colab instance to your chrome remote desktop list.
8. visit http://remotedesktop.google.com/access and your instance will be listed with online status.
9. Click on the link Enter the pin when promted to access your instance.
10. Run the third cell, if you want to mount your gdrive as seperate drive in your instance. 

### What is the purpose of it?
1. VM/Instance with more computational power, memory , storage and bandwidth compared to other free cloud instances
2. No need to register and add payments unlike other VM services.
3. Students can use this to test several projects.
4. Can be used for visual output of data analytics, machine learning. 

# Screenshot

![Colab_Notebook](https://github.com/LokeshJ-Repo/Chrome-Remote-Desktop-Google-Colab-Instance/blob/main/Images/Notebook.png)

![outh_Code](https://github.com/LokeshJ-Repo/Chrome-Remote-Desktop-Google-Colab-Instance/blob/main/Images/SSH_Outh_Code.png)

![Instance_list](https://github.com/LokeshJ-Repo/Chrome-Remote-Desktop-Google-Colab-Instance/blob/main/Images/Instance_List.png)

![Remote_Desktop](https://github.com/LokeshJ-Repo/Chrome-Remote-Desktop-Google-Colab-Instance/blob/main/Images/Remote_Desktop.png)


### Frequently Asked Questions
1. **How long will the instance last**: 
Instance will last for 90mins, if you are not interacting with original colan notebook page. You can frequently interact and run some
code in the original colab notebook page to increase the runtime for more than 90 mins.


# This whole repo is against Google Colab policy and you shouldn't be using it.
> **Why are hardware resources such as T4 GPUs not available to me?**
The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

### Maintained By : [Lokesh J](https://www.linkedin.com/in/lokesh-j-13b844140/)
