# UCSB: iQB2 - Structural Biology Modlule

![banner](banner/banner.png)

<!-- ## Homework

Homework was posted [here](https://github.com/nv-ucsb-courses/iqb2/tree/main/homework). Return by email by December 10nd, 11:59PM.

## Presentation Order

| Name               |  Time          |  Paper |
|--------------------|----------------|--------|
| **Kat**            |  10:00 - 10:20 | CryoCLEM: Anderson et al. 2017 |
| **Alejandra**      |  10:20 - 10:40 | Bacteriophage: Leiman et al. 2004 |
| **Timothy**        |  10:40 - 11:00 | Ribosome: Jobe et al. 2019 |
| *Break*            |  11:00 - 11:10 |   |
| **Anna**           |  11:10 - 11:30 | CryoFIB: Rigort et al. 2010 |
| **Anthony**        |  11:30 - 11:50 | RNA: Bonilla & Kieft 2022 |
| **Chris**          |  11:50 - 12:10 | SARS-CoV-2: Barcena et al. 2020 |
| *Lunch Break*      |  12:10 - 1:00  |   |
| **Fillan**         |  1:00 - 1:20   | CryoDRGN: Zhong et al. 2021 |
| **Cuiyi**          |  1:20 - 1:40   | 200kV: Wu et al. 2020 |
| **Sichu**          |  1:40 - 2:00   | Bacteriophage: Hu et al. 2015 |
| **Dallin**         |  2:00 - 2:20   | Graphene: Liu et al. 2019 |
| *Break*            |  2:20 - 2:40   |   |
| **Mira**           |  2:40 - 3:00   | BetaGal: Bartesaghi et al. 2015 |
| **Andrew**         |  3:00 - 3:20   | Proteasone: Asano et al. 2015 |
| **Ben**            |  3:20 - 3:40   | EVs: Koifman et al. 2017 |

As you can see, the schedule is pretty tight. Please make sure you do not go over your alloted time, otherwise I will have to cut you off. 

Here is the Python code I used to get the randomized list:

```python
from random import shuffle
lst = [i[:-1] for i in open('student_list.txt').readlines()]
shuffle (lst)
for name in lst: print(name)```

-->

## General Information

|               | Name                  | Email                    | 
----------------|-----------------------|--------------------------|
|**Instructor** | Niels Volkmann        | nvo@ucsb.edu             | 
|**TA**         | Trent Llewellyn       | trentllewellyn@ucsb.edu  |
|               |                       |                          |
|**Location**   | BSIF 1211             |                          |

## iClicker
We will use iClicker in class starting on Thursday 11/25. If you have not already done so, please make sure you have a UCSB iClicker student account ready. 
Here is a [link](https://help.lsit.ucsb.edu/hc/en-us/articles/360054938191-iClicker-Cloud-for-Students) with the pertinent information. 
The join link for the course is [here](https://join.iclicker.com/SRHU). If the ink does not work, try searching for "iQB2 - Structural Biology Module" in the iClicker search interface. 
Be aware that the in-class iClicker activities will count towards your grades. I will give credit for participation only, the correctness of the answers will not influence the grades. 

## Grading
20% Participation including iClicker polls and quizzes, 25% Practicals, 25% Presentation, 30% written Homework

## Presentation Format
20 minutes presentation (sharp), + 10 minutes for questions. Papers can either be selected from the list provided 
[here](https://www.dropbox.com/scl/fo/kv4v3au5fki352e3mszg8/h?rlkey=8nesful6u3hpb1r26u5x9wdly&dl=0) (first come first serve) 
or from the general literature upon approval by the instructor. 

## Course Schedule
The following is the approximate schedule for this course. Exact order is subject to change.

|Day	| Date	| 10:00-10:50	| 10:50-11:05	| 11:05-12:00	| 12:00-1:00 | 1:00-4:00  |
|-----|-------|-------------|-------------|-------------|------------|------------|
|Monday	| 11/24	| Lecture	| Short Break	| Lecture	| Lunch Break	| Processing Practicals |
|Tuesday | 11/25	| Lecture	| Short Break	| Lecture	| Lunch Break	| Processing Practicals |
|Monday	| 12/01	| Lecture	| Short Break	| Processing Practicals	| Lunch Break	| CryoEM Sample Prep Lab Visit  |
|Tuesday	| 12/02	| Lecture	| Short Break	| Processing Practicals	| Lunch Break	| CryoEM Facility Visit |
|Thursday	| 12/04	| Lecture	| Short Break	| Processing Practicals	| Lunch Break	| Processing Practicals (ends at 3PM) |
|Friday	| 12/05	| Presentations	| Short Break	| Presentations	| Lunch Break	| Presentations |

<br>
<br>

## Login Instructions
Replace the '#' signs in the code blocks below with your assigned number (see table)

### Powershell (Windows)

```
$env:DISPLAY="localhost:0.0"

ssh -Y user0#@lama.chem.ucsb.edu

     password: igb2_user0#

cd practicals/relion/tutorial
relion &
```
### Terminal (Apple or Linux)

```
ssh -Y user0#@lama.chem.ucsb.edu

     password: igb2_user0#

cd practicals/relion/tutorial
relion &
```
<br>

| Name      | # | GPU id |
|-----------|---|:------:|
| Brennen   | 1 |    0   |
| Pearly    | 2 |    0   |
| Katherine | 3 |    1   |
| Max/Ani   | 4 |    1   |
| Xieergai  | 5 |    2   |
| Binbin    | 6 |    2   |
| Izaiah    | 7 |    3   |
