# exam-randomizer

From a directory of exam questions, generate an exam with each question randomly chosen from a pool of questions.

Three different options to set up directory:
1. [Option 1 - Separate Files for Each Question Option](#option-1)
2. [Option 2 - One File With All Options For Each Question](#option-2)
3. [Option 3 - One File For All Questions](#option-3)

<hr>

<a id="option-1"></a>
## Option 1 - Separate Files for Each Question Option

### Directory Structure

In order to run this script, the directory should be set up as follows:

- All files should be centralized in one directory (e.g. `exam`).
- There should be a _config.yml file located inside of the directory.
- There should be a _qs directory that contains all exam questions.
- Each exam question should have its own separate directory (e.g. `q1`, `q2`, etc.)
- Each question directory should have at least 


(In some directory called `exam`)

```
.
├── _config.yml
├── _qs
│   ├── q1
|   |   ├── 1-1.txt
|   |   ├── 1-2.txt
|   |   ├── 1-3.txt
|   |   └── ...
│   ├── q1
|   |   ├── 2-1.txt
|   |   ├── 2-2.txt
|   |   ├── 2-3.txt
|   |   └── ...
|   ├── q3
|   ├── q4
|   ├── q5
|   ├── q6
|   └── ...
```  

<hr>

<a id="option-2"></a>
## Option 2 - One File With All Options For Each Question

<hr>

<a id="option-3"></a>
## Option 3 - One File For All Questions