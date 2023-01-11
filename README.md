PYTHON:
LIST
#structure of list:
languages=["tamil","english","telungu"]
print(languages)      

list can contains different data types:  lst=["abi",1,false,0.1]
list elemetns can be accessed by index of the elements :
 lst=["abi",1,false,0.1]
 lst[2]   #output: false
 lst[-1]  #output:0.1
 
 we can do slicing list also:      languages=["tamil","english","telungu","malayalam"]
 lst[0:2]   #output:['tamil', english]
 
 list can be nested:     x = ['a', ['bb', ['ccc', 'ddd'], 'ee', 'ff'], 'g', ['hh', 'ii'], 'j']
                         print(x)     #output will be same as above x
                         print(x[0], x[2], x[4])  #output: a,g,j
                         print(x[1])  #output: ['bb', ['ccc', 'ddd'], 'ee', 'ff']
                          
                          we can also print elements in the sublist:
                          print(x[1][0])    #output:'bb'
                          print(x[1][1])    #output:['ccc', 'ddd']
                          printr(x[1][2])   #output:'ee'

list are mutable: we can modify the list items
                      languages = ["tamil","english","telungu"]  
                      print(languages.append("malayalam")    #output:['tamil','english','telungu','malayalam']
                      del(languages[2])
                      print(languages)                       #output:['tamil','english','malayalam']
