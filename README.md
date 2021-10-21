# Work-Stuff
## This is to tell about any experience in work that I have.
> I never really worked on a _real job_ before. 
> I am mainly focusing on studying in college for now before actually thinking about going to work.

### Education
> While I am studying in College. I actually graduated from High School and I am the **1st generation** in my family to enter a college.

## My Past
> But growing up I did do things that seem like manual jobs like:
* Moving blocks
* Picking up trash
* Cleaning any remaing trash
* and some other things as well
> This was actually just helping out my dad who is a [masonry worker](https://www.masonrymagazine.com/wp-content/uploads/2017/08/shutterstock_220694557.jpg.jpeg)and is recently started his own company as well.
> My mom works in a factory that creates parts for something. I do not know what parts specifically but I think it was car parts or something small like nails or screws.

## Siblings
> My little sister is actually hoping to go to the an [Art](https://kcai.edu) Institution or to the [Columbia College](https://www.ccis.edu) because she is pursuing a bachelors degree on [photography](https://i.ytimg.com/vi/ejNIow5DPUM/maxresdefault.jpg)
> 
> My older sister is actually married and with a 1 year old child named Isabella. The name is from her mother-in-law who is currently living with them to help take care of the child. She is working in a Costco but wants to continue studying in business.
# Random Code
> This is a code that was created to see how many numbers are in a file and estimate the following:
* Mean
* Median
* Average
* Range
* Max.
* Min.


def main():
    
    try:
        filename = input("Enter the File Name: ")

        f=open(filename)
        c=0
        maxi=(sys.maxsize)
        mini=(sys.maxsize)

        total=0
        avg=0.0
        for line in f:
            i=int(line.strip())

            c+=1
            total+=i
        if i> maxi:
            maxi=i
        if i<mini:
            mini=i
        print("FileName: ",filename)
        print("Sum: ",total)
        print("count: ",c)
        print("Average: ",avg)
        print("Max: ",maxi)
        print("Min: ",mini)
        print("Range: ",(maxi-mini))

        f.close()
    except:
        print('File Not Found')

choice=input('Would you like to evaluate another file? (Y/N)')

choice=choice.lower()

if (choice !='Y'):
    
    do_filename = False
    

main()


