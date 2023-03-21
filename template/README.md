# ![Bulut Bilisimciler](https://github.com/Bulut-Bilisimciler/template/blob/master/assets/EN2-center.png?raw=true)


## Step 1

Create a file with the name of the technology for which you will write the script(Ex: Git, Go or Linux...). You can think of these files as the root directory.

![Create Base File](https://github.com/YunusEmreAlps/bb-scenario-template/blob/master/md_images/create_base_file.png?raw=true)

<pre>
  <b>template</b>
    |__<b>Linux</b> (Step 1)
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
      |__<b>subject-name-1</b> (Step 2)
        |__en_finish.md
        |__en_intro.md
        |__en_step1.md
        |__index.json
        |__tr_finish.md
        |__tr_intro.md
        |__tr_step1.md
      |__<b>subject-name-2</b> (Step 2)
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
      |__<b>subject-name-1</b>  (Step 2)
        |__en_finish.md (Step 3)
        |__en_intro.md  (Step 3)
        |__en_step1.md  (Step 3)
        |__index.json
        |__tr_finish.md (Step 3)
        |__tr_intro.md  (Step 3)
        |__tr_step1.md  (Step 3)
      |__<b>subject-name-2</b> (Step 2)
        |__en_finish.md (Step 3)
        |__en_intro.md  (Step 3)
        |__en_step1.md  (Step 3)
        |__index.json
        |__tr_finish.md (Step 3)
        |__tr_intro.md  (Step 3)
        |__tr_step1.md  (Step 3)
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
      |__<b>subject-name-1</b>  (Step 2)
        |__en_finish.md (Step 3)
        |__en_intro.md  (Step 3)
        |__en_step1.md  (Step 3)
        |__index.json (Step 4)
        |__tr_finish.md (Step 3)
        |__tr_intro.md  (Step 3)
        |__tr_step1.md  (Step 3)
      |__<b>subject-name-2</b> (Step 2)
        |__en_finish.md (Step 3)
        |__en_intro.md  (Step 3)
        |__en_step1.md  (Step 3)
        |__index.json (Step 4)
        |__tr_finish.md (Step 3)
        |__tr_intro.md  (Step 3)
        |__tr_step1.md  (Step 3)
    |__<b>README.md</b>
</pre>

---

### View of Files on the Platform

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
