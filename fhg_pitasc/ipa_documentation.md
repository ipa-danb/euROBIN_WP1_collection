# Robothon Grand-Challenge documentation template
**Table of content:**
- [Robothon Grand-Challenge documentation template](#robothon-grand-challenge-documentation-template)
  - [The bare minimum of documentation of any robotic project should include:](#the-bare-minimum-of-documentation-of-any-robotic-project-should-include)
  - [The exeptional good documentation also includes:](#the-exeptional-good-documentation-also-includes)
  - [Solution overview](#solution-overview)
  - [Programs](#programs)
    - [Hardware dependencies](#hardware-dependencies)
    - [Software dependencies](#software-dependencies)
  - [How to run](#how-to-run)
  - [Solution in-dept description](#solution-in-dept-description)
  - [Authors](#authors)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>



## The bare minimum of documentation of any robotic project should include:

TODO
And will make you able to run the solution on a identiacly workcell without prior knowlegde of your solution. See it as it will make yourself able to use your solution again in 2 years.

## Solution overview

TODO


The good solution overview has:
- [ ] TODO: A picture of the workcell and solution
- [x] Gripper Fingers
- [ ] A diagram of software and hardware components and their connections
- [ ] A small description, what is developed, most interesting with this solution and what is it inspired by.

## Programs

| Order | Name                 | Force-Controlled? | Position-Controlled? | Velocity-Controlled? |
|-------|----------------------|-------------------|----------------------|----------------------|
| 1     | Touch button         | Observed          | x                    | -                    |
| 2     | Grip probe plug      | Observed          | x                    | -                    |
| 3     | Insert probe plug    | Controlled        | x                    | -                    |
| 4     | Grab slider          | -                 | x                    | -                    |
| 5     | Move slider          | Observed          | x                    | -                    |
| 6     | Open Door            | Controlled        | -                    | x                    |
| 7     | Pick probe (box)     | Observed          | x                    | -                    |
| 8     | Place probe (box)    | Controlled        | x                    | x                    |
| 9     | Pick probe (holder)  | Observed          | x                    | -                    |
| 10    | Place probe (holder) | Controlled        | x                    | -                    |
| 11    | Contact probe        | Controlled        | x                    | -                    |
| 12    | Cableing             | -                 | x                    | -                    |

### Hardware dependencies

| Hardware type     | Model              | OS/Driver version | Note/Picture                                                                                          |
|-------------------|--------------------|-------------------|-----------------------------------------------------------------------------------------------|
| Robot             | Universal robot - UR5e | SW 5.13.1         | [Link for official site](https://www.universal-robots.com/products/ur5-robot/)                |
| 3D printed finger | Costume made       | N/A                | (see folder) |
| Computer          | IPC Nuvo-5002E    | ubuntu 20.04  |                                                                                               |
| Camera            |         None           |                   |                                                                                               |
| Gripper           |    Weiss Robotic WSG-50-110                |        [Link](https://github.com/ipa320/ipa325_wsg50)           |        [Link](https://weiss-robotics.com/de/wsg-series/product/wsg-serie/selectVariant/wsg-50-110/)                                                    |
### Software dependencies
| Name          | Version / git commit / placement in repository                                  | What                                                 | Note (Third-party, commercial, homemade etc.) |
|---------------|---------------------------------------------------------------------------------|------------------------------------------------------|-----------------------------------------------|
| pitasc          | [See here](https://www.pitasc.fraunhofer.de/)                                                                           | Robot programming framework                 | Internal                                  |
| UR5e ROS Driver | [See here](https://github.com/UniversalRobots/Universal_Robots_ROS_Driver)                                                                           | Robot programming framework                 | Public                                  |
| g_compensator | [See here](https://github.com/ipa320/g_compensator)                                                                       | Gravity Compensation                 | Public                                  |
| WSG50 Driver | [See here]([https://github.com/ipa320/ipa325_wsg50])                                                                       | Gripper Driver                 | Public                                  |
| Frame Editor | [See here]([https://github.com/ipa320/rqt_frame_editor_plugin])                                                            | Edit TF Frames in ROS                 | Public                                  |


## How to run
The good how to build, run and get started section has:
- [ ] Start pitasc
- [ ] Run programs with `pi_teacher` in rqt



## Authors
The good authors section has:
- [ ] Listed all authors and a way to get in contact with them.

 Daniel Bargmann, FhG IPA, [Github](https://github.com/ipa-danb), [danb@ipa.fraunhofer.de](mailto:danb@ipa.fraunhofer.de)
