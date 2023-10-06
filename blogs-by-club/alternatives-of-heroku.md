---
description: Venturing into varied deployment terrains.
---

# Alternatives of Heroku

## Writers

* [Himanshu Mude](https://github.com/HimanshuMude)
* [Ayush Thasale](https://github.com/Ayush-Thasale-007)



**Heroku** is a popular cloud platform that simplifies the deployment and scaling of web applications and services. It offers a user-friendly interface and a wide range of development tools, allowing developers to focus on their code rather than infrastructure management. With Heroku, you can deploy applications written in various programming languages, such as Ruby, Python, Node.js, and more. It provides features like automatic scaling, continuous integration, and add-ons for databases, caching, and other services, making it a versatile choice for startups, developers, and businesses looking for a hassle-free platform to host and manage their web applications.

But now Heroku has become completely paid and has recently stopped offering its free tier, leaving many developers searching for new options. You must be in search of some better alternatives for hosting your full-stack applications as well, right? In this blog, we will be discussing five different services that offer free tiers for hosting your applications: Railway, Render, Glitch, Netlify and Vercel.

### Some basic things you need to check before you deploy your application on any platform:

#### Step 1: Prepare Your Project

Upload Your Project: Store your project files on a cloud service like Google Drive, Dropbox, or GitHub. Ensure that you have a download link to the project files.

Package Dependencies: Verify and document the dependencies your project needs. You can typically find these in a requirements.txt file or equivalent.

#### Step 2: Customize the Deployment Configuration

Edit Requirements: Modify the requirements.txt (or equivalent) file in your project to include the specific versions of packages used in your project.

Configure Environment: If your project has environment-specific configurations, ensure they are properly set up. This might involve specifying environment variables or configuration files.

Update URLs: If your project uses external resources (e.g., API endpoints, database connections), ensure that the URLs or connection strings are properly configured for the deployment environment.

All of these platforms offer easy deployment options, such as signing up with GitHub and choosing your repo. They also have easy-to-use interfaces, making it simple to set up and deploy your application or API.



## [Railway](https://railway.app/)

<figure><img src="https://lh3.googleusercontent.com/5ETovGEkopLEtuBgPvjZpO2PLS9IXS2WWtRefRjBIIktirEFN6KYjbA5S9GSuain5mRE0jERDzE1Qc5aX7PW7tNhY9bBCmxX_6fCZJC8grSWJ4VUBaCJqPyApAfvnSXLHny9TQUCdwC7mO5T5NKQs2c" alt=""><figcaption></figcaption></figure>

Railway provides a hosting platform with a free trial that allows you to deploy a wide range of applications and databases easily using Docker. You can connect a repository to Railway and host your application without the need to register on their platform. Railway offers three types of plans. The free trial grants access to basic features and includes a one-time $5 credit, providing 1GB of storage and 512 MB of RAM.

<figure><img src="https://lh6.googleusercontent.com/iVZZDnv56ogfFz_r8NYDL1eeLUQHV4CClzms0jyMphRAcK-tozelaMYlkMtyF4cHrab-5tm-JcQU_kn0ILBb6eeKQL4AJ7enZlI9TTQJl-XJdkihgZkqDk6a_AQ439LX1837S-6amX0rT5e2YweMxAQ" alt=""><figcaption></figcaption></figure>

### How to use Railway?

#### Step 1: Start a New Project

Go to the Railway landing page. Click on “Start a new Project”. You will see many ways to start hosting your application.&#x20;

<figure><img src="https://lh4.googleusercontent.com/wZ1sGKs1DIMfHXP8sx53suRSShllwSJ8dFpjUJIBW-KOYvtgjWi_ga4msa6TF5b71bKi79ePfMUG8xw23dK-oazz7yTWAwUoXxA8AZPEUx6LhN4-S98LLhSmTQ39KKLM66vFtN-55DiIf8_zWO4cFIU" alt=""><figcaption></figcaption></figure>

#### Step 2: Connect GitHub Repository

You’ll be using to use the GitHub repository for deploying the application. Click on “Deploy from GitHub repo”. Then you will be prompted to connect your GitHub account with Railway if you haven’t connected it yet. Just follow the steps and after that, you will have a list of repositories to select from to deploy.

<figure><img src="https://lh4.googleusercontent.com/GpRJPAtyGPpfG7ETvVzfM9BcFTGQzT9dbXnR4b7Yc1MXBEp0bVRYnd-W7NzaWMTRAETs98QmGSqm1QwVN1Dx3H23nqT-jB2Dw3LbFJrZ1fX9sQ6Wk0piHrL4EuRtv2Fh0ENoFa-li_fiudLYmeAu-5c" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh4.googleusercontent.com/H7Q-QdAgSt2lZOnLqzey1OTJjVipLdvEXNL5oCE7NtdE_9f8wBKkIchmmXniMUWzSBUguoaop7pu7gUnWU4bb-XeP-2qx-a8iTk8KQoMgo6TeoyPL30h3nxrqVXn2Q9Zqyd-kco5xFKy3nmDKimEQ0A" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh5.googleusercontent.com/aUtZTgLSBUedlr1Zj5_BT6M48EiBltwyQ-qRYokmGQV74c0p42A2oyVDso6lpoJOjBl6-a40eAROq89uA6z-CkqYJfpaHfCRbYIC2hFAs181XIahPme9oKSYQKMxMrxdRtHIsYL2TksExbMjbiiH0J4" alt=""><figcaption></figcaption></figure>

#### Step 3: Select and Deploy

After selecting the repository, you will have the option to deploy the application and add any necessary environment variables. Once you've added the environment variables, the deployment process will begin, it may take some time. When the deployment is completed, you will see the following screen and a green checkmark on your GitHub repository which will indicate the successful deployment of your application.

<figure><img src="https://lh6.googleusercontent.com/CTZ2cCzgxvlpfyMh-ftr1Cq6q8wFH4G7w6yJKFp8PQlQmk785SrqzFGexRojKrtDnBoUX-RJaufco2ZK-LDrDhoPLBCPOYuT_8aXlleRURO7LcwppFXzhroXRr1lJrta2j9ujj7wZiDV1xgW_ufMIbc" alt=""><figcaption></figcaption></figure>

#### Step 4: Access Hosted Site

After Successful deployment, you will have the URL to your hosted site.

You can also have a custom domain if you have a registered domain. Railway by default provides you with their domain.

<figure><img src="https://lh3.googleusercontent.com/x0WchMfsdBGmDXSlEn7YzZeTADIYpdagdIhy16LUTuPTjM2BCm5LOhhGbGtO3JrSKFtgODWNu7l51ow6hGifH8tskCFq69MHoYffhxBTt7qTmu4LTSbYnoINMtkbzoJqQ_hIAUqSS7NIZSfynofWZh8" alt=""><figcaption></figcaption></figure>



## [Render](https://render.com/)

Render is a popular platform that allows you to deploy Node.js apps, Python, Docker, GraphQL, Rust and Golang. It offers a free tier with 1GB of storage and 1GB of bandwidth. It also has a simple and easy-to-use interface.

Render is a unified cloud to build and run all your apps and websites with free TLS certificates, global CDN, private networks and auto deploys from Git.

However, with the free tier, there are certain limitations too. Render spins down a Free web service that goes 15 minutes without receiving inbound traffic. Render spins the service back up whenever it next receives a request to process.

Spinning up a service takes a few seconds, which causes a noticeable delay for incoming requests until the service is back up and running. For example, a browser page load will hang momentarily.

<figure><img src="https://lh3.googleusercontent.com/FUI02RMzXwnbJjM4-QA0n8Aiz2Omk3RMPLPqWGcWQ1wCdGrjX3T7C3vGck76GffJ6XzNh0uiI04YYej5N5ess9wOCMcnQLmTHk36_bEi9bSJ0mPZ3P7VpAmVyE96MIcoxJR8iUpByba6NOp9bA1GawU" alt=""><figcaption></figcaption></figure>

### How to use Render?

#### Step 1: Deployment

Create a Render Service: Sign up for a Render account if you don’t have one already. Create a new service on Render using your preferred source code hosting platform (e.g., GitHub, GitLab).

Configure Deployment: During the service setup on Render, choose a name for your service, select the appropriate environment (e.g., Docker, Node.js, Python), and specify how Render should build and deploy your project.

Access Control: Set access controls and permissions as needed, ensuring that Render can access your project repository.

Deployment Trigger: Render can automatically deploy your project whenever you push updates to your linked repository. Ensure your repository is up-to-date.

#### Step 2: Testing

Live Testing: Once the deployment is complete, you can access your project through the provided URL (e.g., https://service-name.onrender.com). Test your project thoroughly in the live environment to ensure it works as expected.

Monitoring: Monitor the performance and logs of your deployed project using Render's dashboard or any other monitoring tools you've set up.

#### Step 3: Local Testing (Optional)

Local Development Environment: To test your project locally, ensure you have a development environment set up with the required dependencies installed

Run Locally: Start your project locally using the appropriate command for your project type. For example, if it's a web application, you might use a command like python app/server.py serve. If you have Docker installed, you can containerize your project for local testing, similar to the provided Docker command.



## [Glitch](https://glitch.com/)

Glitch is a platform that allows users to create, host and share web applications and APIs. It offers a free tier with 500MB of storage and 1GB of bandwidth. It has a unique feature that allows users to remix existing projects, which makes it easy to get started.

<figure><img src="https://lh4.googleusercontent.com/iHTYcCLbBJO5W6dONfF_iX65N0hH1s-oc5pbC7LJHaVtDkbfrlfQjXRV5o5KVep0-wvNeZ7D0vKM_qWN067bnN4sKDXuKvVn0aXev9bBh1dsoWLoHwna7OK8vkvTwgbHyhKugyOEc4-Qe5K-69V8ADI" alt=""><figcaption></figcaption></figure>

### How to deploy?

#### Step 1: Initialize a Glitch Project

If you haven't already, create a new project on [Glitch](https://glitch.com/). You can create a new project from scratch or use one of their starter templates. Click the "Import from GitHub" button. In the dialog that appears, search for your GitHub repository by name and select it. Glitch will clone that repository into your created new project.

<figure><img src="https://lh6.googleusercontent.com/HYSKzn7j3YX4VQSXXU6x5W6XG7GRvUYtQw1iNzHdODpvimwPGqwl2d5bo5uiugSR9ghzPI5mPtiXFG0pXOW698awnruK6p9hE0wEMU4HoW6fXUCLX1_8OZhsYySdJBiyaEjzrFtRif9YUFczRPOeHNg" alt=""><figcaption></figcaption></figure>

#### Step 2: Edit Your Project

Once your project is ready, you'll be taken to the Glitch code editor. You can edit your project's HTML, CSS, and JavaScript files right in the browser. Make any changes you need to customize your project. You can add new files, install npm packages, and make code modifications as required for your web application.&#x20;

<figure><img src="https://lh3.googleusercontent.com/jQzkiRBuKZ8w1EpR7df1VThYG9owGK-BkT7ttEBVupXVmXvDHggPuQ4XXQB_n-7OoNo6Sp0Yw82IA5wO0OtI8O9g58SkdGKKvGv5E-1ZV98jDpKSHPEOdGoKusUfzZ0oDa8QK1RqgipvH3mKQlsLBVo" alt=""><figcaption></figcaption></figure>

#### Step 3: Configure Your Project (if necessary)

Depending on the complexity of your web application, you may need to configure environment variables, databases, or other settings. You can access these settings from the project dashboard.

#### Step 4: Publish Your Project:

When you're ready to make your project live on the internet, click the "Share" button, and then select "Live App." This will generate a public URL that you can share with others.

<figure><img src="https://lh5.googleusercontent.com/hWpRCovqfljORP-kHnpYujDXplE60BgmJ9HPwAzkMUCrdAHgl_3nbeDWrpCDfQ4BNP5E-C0o5c_IdPioYte1L4V7HGMP7k9-E5fmc1Fcr9apoosrwilZpJBRVBL2xXOwxfo_uUsNlWouoCR1sq-BKEY" alt=""><figcaption></figcaption></figure>

#### Step 5: Keep Your Project Running:

Glitch projects have a limit on their uptime if they're not visited regularly. To ensure your project stays live, you can use services like UptimeRobot to ping your URL regularly.

### What makes Glitch different?

One major difference between Glitch and many other hosting platforms is the way Glitch simplifies the development process by providing an integrated development environment (IDE) directly in the browser.

Traditional hosting platforms typically require users to set up and manage their development environments, including configuring servers, databases, and dependencies. Users need a local development environment on their computers, which can sometimes be complex and time-consuming to set up, especially for beginners.



## [Netlify](https://www.netlify.com/)

Netlify is also another free alternative for Heroku. It provides a simple user experience and deploys your application in a few simple steps. It also provides an option to deploy using CLI  in NodeJS along with GUI on its website. The free tier of Netlify offers 100GB of bandwidth per month and you can purchase extra bandwidth too if required. Netlify's free tier offers 300 build minutes per month. Build minute is the time it takes Netlify to build your site — to run site generators, compile JavaScript, and perform other tasks.

### Steps for deploying your site:

#### Step 1: Connecting GitHub Account

Go to the Netlify dashboard after creating your account and connecting your GitHub to it.

<figure><img src="https://lh5.googleusercontent.com/FzyexkGojKb_pFCtcbTYHgauGaUDEs49ffbL1fkJhmKWlH9cIWfRNlFA1iGzQXilz9w0MHdSQbZ-VoZ0Gd54-lvJcqb3sA-4krt3JF6lYft1FMvpNiidvf8P9fAxpbY19TkWsx2l20_vWCKyIF3Hm0k" alt=""><figcaption></figcaption></figure>

#### Step 2: Selecting project repository

Select Import from Github and select the repository that has all files regarding your application.

#### Step 3: Configuring deployment

Then you can configure your deployment with the deploy command and environment variables can be given.

<figure><img src="https://lh3.googleusercontent.com/QdhZwArlyegbglc1INfvyV4Z1GhsEWWu_PKi1NJoxJUhgzT3awPBcAH6xJgAY91Hww7ovPy7i0T669oaeXoPQyML9Hcn0_YJe8Tisjci5iIenO2j0UyRZwyWZ3dW_0RqVVcBJvgtAtoI11o_jlQnnk8" alt=""><figcaption></figcaption></figure>

#### Step 4: Summary of deployment

After that, you will be redirected to the site overview page. Wait for some time for deployment to finish.

<figure><img src="https://lh5.googleusercontent.com/ZnOCz6EqDwGLihJMMrSQwYrnAxI-InkqqSLuMa1K370vG2uhzQ1Gzi0RrUVuJnntwy5fsVTMc82cf-ot3Fj_h57v8eWre4ITwxF7Ua0WOQbXrASPzNGatUIzOTJrrJBH0WMtZ18JAG2P7SJ51NRlC7s" alt=""><figcaption></figcaption></figure>

Netlify will generate a random name for your application. You can also edit this name later.

<figure><img src="https://lh4.googleusercontent.com/uoyTqZNeDakd1EQ5AMbGzPtiiUn369q3jGfqL5HvEjEYWO663RqNSu_5MkK7QTyCJlsNxKM2DJ5D9GslZBt_fTe1tuHqObml9hY8pQoOzVR8jOK5vEGklZJiS_jmFO29Bd3Mh3hC7a50YXwDjshHKkg" alt=""><figcaption></figcaption></figure>



## [Vercel](https://vercel.com/dashboard)

Vercel is a cloud platform that specializes in hosting static websites, front-end applications, and serverless functions, offering developers a simple and efficient way to deploy and scale their web projects. Below is the plan comparison for Vercel. It offers support for 35+ Frameworks, automatic CI/CD (Git Integration), functions (Serverless, Edge), starter Database (KV, Postgres) and Web Analytics. It also provides 100GB of bandwidth.

<figure><img src="https://lh4.googleusercontent.com/9uW-TlzFtPR9OA_VeOrFDh_7EWKQI6AaLIc81F3TLgnLwXF1HG4NkOAUp8w96y6zjpF1Db6RGwLTgLKW9Y0qPhgIuY2YpmDy1adhj4LxwynHF22lCb9bf20vpthBPLGz5-Aa2eRPh7EMfQrsmyap0pE" alt=""><figcaption></figcaption></figure>

<figure><img src="https://lh5.googleusercontent.com/HgbEQICX3qtDAUv4GUkITVnlsNL0CgVz5wHtEVGA4e5kXDF3Qplvcjnr7wavrBjQkxveTVBK9a8csHkwMd0IMfyGtXyWJ9MWVlo69cRqkOSI9NUuqMwwDVGD3uHQPGP-p-cjub0IE76BQJmVGLvJQ-w" alt=""><figcaption></figcaption></figure>

### Steps to use Vercel:

#### Step 1: Sign Up

Go to the Vercel website (https://vercel.com/) and sign up for an account if you don't have one already.

#### Step 2: Install Vercel CLI (Optional)

Install the Vercel CLI by running npm install -g vercel if you want to use the command-line interface for deployment. As it’s not mandatory, you can continue with simple GUI as well, prefer whichever is comfortable for you and go down the steps.

#### Step 3: Link Your Project to Vercel

Log in to your Vercel account on the Vercel website. Click the "Import Project" button on your Vercel dashboard. After that choose your project's source code repository (e.g., GitHub, GitLab, Bitbucket) and grant Vercel access to it. Remember to select that specific repository and branch only which you want to deploy.

#### Step 4: Configure Deployment Settings

Configure your deployment settings. You can set environment variables, specify build commands, and choose other deployment options. Review and confirm your configuration settings.

#### Step 5: Deploy Your Project

Click the "Deploy" button to start the deployment process. Vercel will automatically build and deploy your project based on your configuration.

You can monitor the deployment progress in real-time on your Vercel dashboard.

#### Step 6: Access Your Deployed Project

Once the deployment is complete, Vercel will provide you with a unique URL where your project is hosted (e.g.,https://your-project-name.vercel.app).

You can access and share your deployed project using this URL.

#### Step 7: Monitor and Manage Your Project

Use the Vercel dashboard to monitor the performance of your deployed project, configure domains, and manage settings.

#### Step 8: Continuous Deployment (Optional)

Set up continuous deployment to automatically redeploy your project whenever you push updates to your repository.

#### Step 9: Custom Domains (Optional)

If you have a custom domain, you can configure it to point to your Vercel deployment using Vercel's domain management tools.



## Conclusion

In today's fast-paced world of web development, having accessible and user-friendly deployment platforms is crucial. Heroku, a beloved choice for many developers, recently shifted to a fully paid model, prompting the search for alternative solutions. In this blog, we explored several free alternatives that cater to various needs and preferences.

**Railway** offers seamless deployment via Docker, making it a breeze to host web applications and databases. With its free trial and a generous one-time grant, it's a solid choice for those just starting their journey.

**Render** stands out with its support for a wide range of programming languages, coupled with a unified cloud platform. Its free tier, featuring 1GB of storage and bandwidth, makes it an attractive option for both beginners and experienced developers.

**Glitch** takes a unique approach by allowing users to remix existing projects, simplifying the development process. With 500MB of storage and 1GB of bandwidth in its free offering, it's a creative playground for building and sharing web applications.

**Netlify** provides a straightforward and user-friendly experience with easy GitHub integration. Offering 100GB of free bandwidth, it's an excellent choice for hosting web applications and static websites.

**Vercel** specializes in hosting static websites, front-end applications, and serverless functions, offering an efficient deployment process and 100GB of bandwidth. It's a go-to platform for front-end developers looking to showcase their projects.

These free alternatives to Heroku offer a wide range of features, making them suitable for small projects, testing, or showcasing your work. However, for larger-scale applications or businesses, it's important to consider paid hosting options that can provide more resources and scalability. As a developer, the world of deployment options is at your fingertips—explore, experiment, and choose the one that best aligns with your project's needs and your development style.

For more information about our club you can visit us on:

* [Website](https://www.wcewlug.org/)
* [Facebook](https://www.facebook.com/wlugclub/)
* [Twitter](https://twitter.com/wcewlug)
* [LinkedIn](https://www.linkedin.com/in/wlug-club-3a9236117/)
* [Instagram](https://www.instagram.com/wcewlug/?hl=en)

\
