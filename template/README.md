# ![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/EN2-center.png?raw=true)


## Step 1

Create a file with the name of the technology for which you will write the script(Ex: Git, Go or Linux...). You can think of these files as the root directory.

![Create Base File](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/create_base_file.png?raw=true)

<pre>
  <b>template</b>
    |__<b>Linux</b> <b>(Step 1)</b>
      |__<b>subject-name-1</b>
        |__en_finish.md
        |__en_intro.md
        |__en_step1.md
        |__index.json
        |__tr_finish.md
        |__tr_intro.md
        |__tr_step1.md
      |__<b>subject-name-2</b>
        |__en_finish.md
        |__en_intro.md
        |__en_step1.md
        |__index.json
        |__tr_finish.md
        |__tr_intro.md
        |__tr_step1.md
    |__<b>README.md</b>
</pre>

## Step 2

After completing the 1st step, we create files according to the subject headings. (You can name it bash-basics-1, basics-1, etc.). We can think of these files as branches of a tree.

![Create Base File](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/create_scenario_file.png?raw=true)

<pre>
  <b>template</b>
    |__<b>Linux</b> (Step 1)
      |__<b>bash-basics-1</b> <b>(Step 2)</b>
        |__en_finish.md
        |__en_intro.md
        |__en_step1.md
        |__index.json
        |__tr_finish.md
        |__tr_intro.md
        |__tr_step1.md
      |__<b>bash-export-1</b> <b>(Step 2)</b>
        |__en_finish.md
        |__en_intro.md
        |__en_step1.md
        |__index.json
        |__tr_finish.md
        |__tr_intro.md
        |__tr_step1.md
    |__<b>README.md</b>
</pre>

## Step 3

We create the following files within each topic header file we create.

- en_finish.md
- en_intro.md
- en_step1.md
- index.json
- tr_finish.md
- tr_intro.md
- tr_step1.md

<pre>
  <b>template</b>
    |__<b>Linux</b> (Step 1)
      |__<b>bash-basics-1</b>  (Step 2)
        |__en_finish.md <b>(Step 3)</b>
        |__en_intro.md  <b>(Step 3)</b>
        |__en_step1.md  <b>(Step 3)</b>
        |__index.json
        |__tr_finish.md <b>(Step 3)</b>
        |__tr_intro.md  <b>(Step 3)</b>
        |__tr_step1.md  <b>(Step 3)</b>
      |__<b>bash-export-1</b> (Step 2)
        |__en_finish.md <b>(Step 3)</b>
        |__en_intro.md  <b>(Step 3)</b>
        |__en_step1.md  <b>(Step 3)</b>
        |__index.json
        |__tr_finish.md <b>(Step 3)</b>
        |__tr_intro.md  <b>(Step 3)</b>
        |__tr_step1.md  <b>(Step 3)</b>
    |__<b>README.md</b>
</pre>

**You can finish the scenarios in one step, but this will make learning long and complex. Therefore, breaking it down into steps will make the learning process easier and more fluid. You can increase en_step1.md and tr_step1.md files as en_stepx.md and tr_stepx.md according to the number of steps.**

![Create MD Files](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/md_files.png?raw=true)

## Step 4

In the last step, we define the files we created in the **index.json** file. We need to enter the steps, the image name to be used and the video link as follows.

```sh
{
    "scenario": {
      "steps": [
        {
          "text": "step1.md" // Adım 1
        }
        {
          "text": "step2.md" // Adım 2
        }
        {
          "text": "step3.md" // Adım 3
        }
      ],
      "intro": {
        "text": "intro.md" // Dersin içeriği ile ilgili girizgâh yapılan dosya
      },
      "finish": {
        "text": "finish.md" // Dersin sonunda elde edilen yetkinliklerin anlatıldığı dosya
      },
      "video": {
        "text": {
          "en": "https://youtube.com/embed/zRiZZwGSl0M", // İngilizce Video
          "tr": "https://youtube.com/embed/zRiZZwGSl0M"  // Türkçe Video
        }
      }
    },
    "environment": {
      "uilayout": "editor-terminal"
    },
    "backend": {
      "imageid": "alpine" // Kullanılacak Image Adı
    }
  }
```

![Index.json](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/index.json.png?raw=true)


<pre>
  <b>template</b>
    |__<b>Linux</b> (Step 1)
      |__<b>bash-basics-1</b>  (Step 2)
        |__en_finish.md (Step 3)
        |__en_intro.md  (Step 3)
        |__en_step1.md  (Step 3)
        |__index.json <b>(Step 4)</b>
        |__tr_finish.md (Step 3)
        |__tr_intro.md  (Step 3)
        |__tr_step1.md  (Step 3)
      |__<b>subject-name-2</b> (Step 2)
        |__en_finish.md (Step 3)
        |__en_intro.md  (Step 3)
        |__en_step1.md  (Step 3)
        |__index.json <b>(Step 4)</b>
        |__tr_finish.md (Step 3)
        |__tr_intro.md  (Step 3)
        |__tr_step1.md  (Step 3)
    |__<b>README.md</b>
</pre>

---

## How to Add Your Course to a Platform: Step-by-Step Guide

Bulut Bilisimciler is a popular online learning platform that focuses on cloud computing and related technologies. If you're an expert in this field and want to share your knowledge by adding your course to Bulut Bilisimciler, here's a step-by-step guide:

- **Step 0: You Can Watch All Step From [YouTube](https://www.youtube.com/watch?v=k7X2-GLbCkg)**

- **Step 1: Go to the Bulut Bilisimciler Website**
Open your web browser and go to the Bulut Bilisimciler website at https://bulutbilisimciler.com/.

- **Step 2: Sign up or Log in**
If you're a new user, click on the "Sign Up" button on the top right corner of the website to create a new account. Fill in the required information, such as your name, email address, and password. If you already have an account, click on the "Login" button and enter your credentials to log in.

![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step1.png?raw=true)
- **Step 3: Access the Instructor Dashboard**
Once you're logged in, you'll be directed to your profile. If you're a new user, you may need to complete a profile setup process, including providing additional information about yourself and your expertise.

![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step2.png?raw=true)
![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step3.png?raw=true)
- **Step 4: Click on "Create a New Course"**
In your instructor dashboard, click on the "Create a New Course" button or similar option. This will initiate the course creation process.

![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step5.png?raw=true)
![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step6.png?raw=true)

- **Step 5: Provide Course Information**
Fill in the required course information, such as the course title, subtitle, and description. Be sure to provide a compelling description that clearly outlines what your course is about and what students will learn.

![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step8.png?raw=true)
![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step9.png?raw=true)
**Step 6: Upload Course Content**
Next, upload your course content, which may include video lessons, written materials, quizzes, assignments, and any other relevant resources. Bulut Bilisimciler supports various file formats, so you can upload your content in the format that best suits your course.

![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/step7.png?raw=true)
**Step 7: Customize Course Settings**
Customize your course settings, such as language, visibility, and other options. You can also set up coupons or discounts for your course if applicable.

**Step 8: Preview Your Course**
Before publishing your course, take the time to preview your course content and settings to ensure everything is accurate and complete. Use the preview feature provided by Bulut Bilisimciler to review your course from a student's perspective.

**Step 9: Publish Your Course**
Once you're satisfied with your course content and settings, click on the "Publish" button to make your course live on Bulut Bilisimciler. Your course will be reviewed by the platform to ensure it meets their quality standards.

---
## View of Files on the Platform

- **Courses**
![Scenarios](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/lesson.png?raw=true)
- **Displaying Scenarios**
![Scenarios](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/scenario_list.png?raw=true)
- **Running the Scenario**
![Specific Scenario](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/scenario_tab.png?raw=true)
- **Scenario Start  (tr_intro.md)**
![tr_intro.md](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/tr_intro.md.png?raw=true)
- **Scenario Steps (tr_step1.md)**
![tr_step1.md](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/tr_step1_top.png?raw=true)
![tr_step1.md](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/tr_step1_bottom.png?raw=true)

- **Scenario Finish (tr_finish.md)**
![tr_finish.md](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/tr_finish.md.png?raw=true)