# Robothon Grand-Challenge documentation template
**Table of content:**
- [The bare minimum of documentation of any robotic project should include:](#the-bare-minimum-of-documentation-of-any-robotic-project-should-include-)
- [The exeptional good documentation also includes:](#the-exeptional-good-documentation-also-includes-)
- [Solution overview](#solution-overview)
  * [Hardware dependencies](#hardware-dependencies)
  * [Software dependencies](#software-dependencies)
- [How to run](#how-to-run)
- [Solution in-dept description](#solution-in-dept-description)
- [Authors](#authors)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>



## The bare minimum of documentation of any robotic project should include:
- [ ] A solution overview
- [ ] A software and hardware dependencie list of any kind
- [ ] A how to build, run, and get started section
- [ ] An Author list with contact infomation
- [ ] Citations to inspired works and dependencies

And will make you able to run the solution on a identiacly workcell without prior knowlegde of your solution. See it as it will make yourself able to use your solution again in 2 years.

## The exeptional good documentation also includes:
- [ ] An indepth solution description
- [ ] A fully functional virtualised developer environment (Like a docker img etc.)
- [ ] Is tested by somone external
- [ ] A how and where to contribute section

## Solution overview
The good solution overview has:
- [ ] A picture of the workcell and solution
- [ ] A diagram of software and hardware components and their connections
- [ ] A small description, what is developed, most interesting with this solution and what is it inspired by.

 [bisCARI 2023 Team](https://github.com/JRL-CARI-CNR-UNIBS/Robothon2023/) made a nice example. 

### Hardware dependencies
The good hardware depenency list has:
- [ ] Model
- [ ] OS/Driver version
- [ ] Link to where/how it can be aquired or original manufacture

An example of how it could look, tables generated with [tablesgenerator.com](https://www.tablesgenerator.com/markdown_tables):
| Hardware type     | Model              | OS/Driver version | Note/Picture                                                                                          |
|-------------------|--------------------|-------------------|-----------------------------------------------------------------------------------------------|
| Robot             | Universal robot - UR5e | SW 5.13.1         | [Link for official site](https://www.universal-robots.com/products/ur5-robot/)                |
| 3D printed finger | Costume made       | N/A                | [Link for CAD](https://sketchfab.com/3d-models/robotic-hand-3e284b06bbb84d858f85f7a246cd65df) |
| Computer          | ThinkPad p51       | ubuntu 20.04.6    |                                                                                               |
| Camera            |                    |                   |                                                                                               |
| Gripper           |                    |                   |                                                                                               |
### Software dependencies
The good software depenency list has:
- [ ] Listed all packages, software etc. needed to run the solution!
- [ ] Version or git commit used in project
- [ ] Link to where/how it can be aquired

| Name          | Version / git commit / placement in repository                                  | What                                                 | Note (Third-party, commercial, homemade etc.) |
|---------------|---------------------------------------------------------------------------------|------------------------------------------------------|-----------------------------------------------|
| Python3       | [3.6.0 ](https://www.python.org/downloads/release/python-360/)                                                                          | General-purpose programming language                 | Third-party                                   |
| Numpy         | [1.24.3](https://pypi.org/project/numpy/1.24.3/)                                | Python array computing                               | Third-party                                   |
| opencv        | [4.7.0.72](https://pypi.org/project/opencv-python/4.7.0.72/)                    | Computer vision                                      | Third-party                                   |
| ROS2          | [Foxy Fitzroy](https://docs.ros.org/en/foxy/Releases/Release-Foxy-Fitzroy.html) | Robot Operating System (ROS), set of robot libraries | Third-party                                   |
| Vision module | [Link to module]()                                                              | Control of vision                                    | Homemade                                      |
|               |                                                                                 |                                                      |                                               |

## How to run
The good how to build, run and get started section has:
- [ ] All downloads, setups, clicks, commands and actions needed to run the version listed.

## Solution in-dept description
The good how to build, run and get started section has:
- [ ] Descripes the solution and all it's interesting parts a bit more in depth, how it can be modified and what their porpuse is.



## Authors
The good authors section has:
- [ ] Listed all authors and a way to get in contact with them.

 Mikkel Labori Olsen, [Github](https://github.com/dk-teknologisk-miol), [LinkedIn](https://www.linkedin.com/in/mikkel-labori-olsen/), [miol@teknologisk.dk](mailto:miol@teknologisk.dk)