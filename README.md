# Stuxnet-Model
Stuxnet Model using Metropolis Meta Model framework
## Instructions to use Code
1. Download the latest version of Metropolis from [here](https://embedded.eecs.berkeley.edu/metropolis/)
2. Replace the "metropolis-1.1.4/examples/pip" folder with the folder "Stuxnet-Model/pip". This contains the Stuxnet model.
3. Replace the following files in your Metropolis folder with my files from plt folder-
>>* plt/TTLtemplate/yapi2TTL.mmm
>>* plt/TTLtemplate/yapirefTTL.mmm
>>* plt/yapitemplate/yapicosim.mmm
>>* plt/yapitemplate/yapi.mmm
4. Follow the instructions in the makefile (metropolis-1.1.4/makefile) in main metro directory
>>* configure
>>* make
5. To run the example in the terminal, got to metropolis-1.1.4/examples/pip/map -
>>* type "make"
>>* ./run.x >& run.out
>>* wait for a few seconds and then Ctrl+C. The result is present in run.out file.
