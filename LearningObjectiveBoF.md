# Notes from learning objectives BoF

1) What would we want people to know exciting a freshman class taught with R or Python?  
a) Feeling like you can do it.  
b) Accessing data (locally, from web).  
c) Macipulate data (access columns, split data).  
d) Basic visualization.  
e) Hypothesis testing.   

2) What would we want students to leave a bioinformatics class with?  
a) Ability to explain common data types.  
b) Converting and reformating data.  
c) Ability to use Google to find the meaning of an error message.  
d) Understand assumptions of models used in class and if they fit the provided data.  
e) Familiarity with one programming language.  

## Raspberry Pi Group

### Potential uses of Pi

-   Teaching without reliable internet
    -   Can set up as local server for sharing data with/among students

-   Teaching high-performance computing at institution that does not provide
    HPC resources for teaching
    -   Can teach HPC concepts with mini pi cluster
    -   Comp power would be limited, but should be sufficient for teaching
        basic principles parallelization/scaling
    -   Even if institution provides HPC resources for teaching, a mini pi
        cluster could be used as the "bag of flour" or "egg" baby:
        -   Once students learn not to "break" pi cluster, then they can use
            institutional HPC resources

-   Integrating comp skills into core biology curriculum
    -   Work Pis into curriculum as early as Intro Bio
    -   Students can use them for entire scientific process:
        -   Can use accessories to collect video/photo/temperature/motion/etc.
            data in lab
        -   Use basic scripting to organize and clean data (lab and/or lecture)
        -   Use scriptingto visualize and analyze data (lab and/or lecture)
    -   Expose students early to hardware and computing; sets them up for
        learning advanced comp bio material in upper level courses (and beyond)
    -   Doing this will inevitably lead to the excuse "the dog ate my raspberry pi"

### Potential problems with Pi

-   Raspberry Pis have ARM processor
    -   May limit some software
    -   Can solve by creating custom images of OS before hand
    -   Also, there are Intel chip options (e.g., Atomic Pi)

-   Cost of Pi is cheap, but add in peripherals (keyboard, mouse, monitor) and
    your getting close to cost of inexpensive laptop
    -   Unlike laptop, Pi is modular; students can keep $10 pi, and the
        peripherals can be kept and reused semester to semester.
