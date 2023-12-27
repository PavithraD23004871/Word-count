# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood
### Step 2: 
Read the text using read() function. 
### Step 3: 
Split the text using space separator. We assume tha words in a sentence are separated by a space character
### Step 4:  
The length of the split list should equal the number of words in the test  file.
### Step 5: 
You can refine the count by cleaning the string prior to splittong or validatting the words after splitting
### Step 6: 
End the program
## PROGRAM:
Developed by : pavithra.D
Registered number: 212223230146

def wordcount(filename):
    count=0
    with open(filename,"r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
### OUTPUT:
![WhatsApp Image 2023-12-27 at 18 40 37_ba5ad254](https://github.com/PavithraD23004871/Word-count/assets/138955967/aff0e52a-6acc-4ac1-995d-582c18dec1fa)
![WhatsApp Image 2023-12-27 at 18 40 37_78a82c50](https://github.com/PavithraD23004871/Word-count/assets/138955967/5c020212-6f94-425e-b281-713bca412d58)



## RESULT:
Thus the program is written to find the word count from a text.
