# Image-preprocessing (Under Process)
changing the dimension of images from and copying results to fixed directory

Pre requisite for implementing this file:
check PIL,GLOB,OS Module of python
python 3.5+ compatible and tested on bulk Image Data set to use it as input to Convolutional neural networks
Set any dimension of output image in line im=img.resize((256,256)) I choose (256,256) as my need,you can take your own desired demension
properly copy the path of your destination directory and assign it to outpath within single or double quote
also copy the source directory path,i mean the image dataset folder path and paste it in glob.glob() with file extension name
any extension .in my case my dataset it is in .jpg so i used .jpg
Also one can get desired extension by writing the desired extension name in 
save_fname = os.path.join(outpath, os.path.basename(filename)+'.jpg')
    im.save(save_fname)
 in mycase i required .jpg ,one can put .png for png output extension and so on.
 
