# Arch Linux Install - It doesn't get any easier

_Make the arch linux install process simple and easy in three steps!_

<!--step0-->

Have you ever wanted a linux distro that can do more? Be configured the way you want it to be? A distro that isn't linux mint or ubuntu> Then this tutortial is for you! 

Arch linux is quite popular in the linux community and for good reason. The process of setting up Arch will force you to think of why you want something and figure out how things work internall. In the end you'll end up with a system that is exactly as you want it and you know exactly how it works (as you've set every single thing up yourself).

Might sound daunting, but it's really not that bad, especially with the experience you've likely gathered using the distributions you've mentioned. You probably encountered the Arch wiki using those distributions. Using Arch, its information is even more accure and valuable!

However for pure beginners the process of manually setting up arch might seem akin to learning a foreign language. Time and time again you hear people getting discouraged because they encounter this or that error and stay stuck on those issues for days until they give up. 

Well don't worry, the devs have your back! What a lot of people don't know is that there actually is a way to make the setup simple by just one command line. Don't believe me? Let's get started then! 

- **Who is this for**: Beginners, students, Linux enthusiasts.
- **What you'll learn**: How to install arch linux through command archinstall.
- **What you'll build**: We'll build a simple arch linux operating system of your liking. 
- **Prerequisites**: Your computer must be x86-64 compatible, have a secure and stable internet connection, and have a USB drive with a storage capacity of at least 2 GB. You will also need at least 512 MB of RAM and 1 GB of storage. _It is already assumed you know how to get the iso file, flash it into a usb drive, and boot your computer into its BIOS._
- **How long**: This course is three steps long and takes less than one hour to complete.

<!--endstep0-->

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

<details id=1>
<summary><h2>Step 1: Arch Install</h2></summary>

The first step is to put the command archinstall. Then I will guide you activity by activity until 
 
### :keyboard: Activity: Update archinstall.

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Under your repository name, click **Settings**.
1. Click **Pages**, in the "GitHub Pages" section, use the Source drop-down, then select **main branch**.
1. Wait about _one minute_, then refresh this page for the next step.
   > Turning on GitHub Pages creates a deployment of your repository. GitHub Actions may take up to a minute to respond while waiting for the deployment. Future steps will be about 20 seconds; this step is slower.

</details>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

<details id=2>
<summary><h2>Step 2: Arch Installation</h2></summary>

_You turned on GitHub Pages! :tada:_

We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Update archinstall

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
    ```yml
    theme: minima
    ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. Wait about 20 seconds then refresh this page for the next step.

Now you are officially in archinstall!

 
 
 
</details>

<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked the homepage content was not empty.
-->

<details id=3>
<summary><h2>Step 3: Arch Boot</h2></summary>

_You've installed Arch! :tada:_

You can customize your homepage by adding content to either an `index.md` file or the `README.md` file. GitHub Pages first looks for an `index.md` file. Your repository has an `index.md` file so we can update it to include your personalized content.

### :keyboard: Activity: Create your homepage

1. Browse to the `index.md` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Type the content you want on your homepage. You can use Markdown formatting on this page.
1. (optional) You can also modify `title:` or just ignore it for now. We'll discuss it in the next step.
1. Commit your changes to the `my-pages` branch.
1. Wait about 20 seconds then refresh this page for the next step.

</details>
