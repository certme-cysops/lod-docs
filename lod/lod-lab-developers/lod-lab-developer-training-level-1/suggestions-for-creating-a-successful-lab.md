# Suggestions for creating a successful lab

When you have completed the design and implementation of your lab, here are some suggestions of items to do before you ?optimize? the image for use as a demo or as a lab:

1. Turn off any sleep options in the **Power Options**.
1. Turn off **Windows Updates** service.
1. Set the **Performance** options in **System Properties** to **Adjust for best performance**.
1. Ensure all applications used are functional and will not expire during the life of series use (i.e. do not use trial or beta applications that have hard-set expiration dates outside of when the lab is launched)
1. Ensure VMs can talk to each other, if necessary

Enhance the image as necessary
1. Make a differencing disk after all changes are made
1. Rearm OS and applications
1. Make a final differencing disk
1. Create a **Start State**

In the **Lab Profile** edit page on **Virtual Machines** tab:

1. For the virtual machine that the user will interact with first, check **Default selection**.
1. Set **Startup delays** on VMs, as necessary, for proper connection between machines

