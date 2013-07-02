### Powers Process Control Language (PPCL) Library ###

Powers Process Control Language (PPCL) Library. Example programs and generic code snippets.

See https://gist.github.com/delphian/5906264 For the standard template. All programs should conform to this generic template style.

#### Powers Process Control Language ####

PPCL (Powers Process Control Language) is the programming language used for many Siemens made controllers. Controllers are generally used to automate industrial or commercial process, but could provide control automation to something as simple as yard sprinklers. Controller devices are where the electronic world meets physical.

A typical PPCL programmer will be trained to make use of numerous GOTO statements. Unfortunately this results in spaghetti code. Several of the example programs here do not use a single GOTO statement, these flow structures are completely alien to a typical PPCL programmer, thus are not representative of what is found in the field.

#### Language Overview ####

 * Basic style syntax with line numbering.
 * Programmable functions only achieved via Gosub method.
 * If, Then, Else conditionals may only contain a single line of code to execute for each condition.
 * No native function to return the remainder of a division.
 * No native looping control flow.
 * Native functions can not be embedded for their return value.
 * No virtual controller on the PC (No functions to interact with a computer OS).
 * Global namespace only.

#### Installation ####

 1. `git clone --recursive https://github.com/delphian/ppcl-library.git`.
 2. `cd ppcl-library`.

Although there are no functions to easily interface with a third party, most Siemens building level automation controllers come with a telnet port. It does not take much work to code up a simple interface.
