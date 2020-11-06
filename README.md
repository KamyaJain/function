# function
#Designed by KamyaJain 

def most_frequent(string): 

    my_dict=dict()
    for i in string:
        my_dict[i]=string.count(i)
    descend_keys=sorted(my_dict,key=my_dict.get,reverse=True)
    for i in descend_keys:
        print(i,'=',my_dict[i])

most_frequent("Mississippi")
