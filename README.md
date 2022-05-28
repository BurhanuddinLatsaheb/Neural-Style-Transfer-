# Neural-Style-Transfer-
Neural Style Transfer  Using InceptionNet V3
Neural Style Transfer is the technique of blending style from one image into another image keeping its content intact. The only change is the style configurations of the image to give an artistic touch to your image.
                                    
                                        OR

Neural Style Transfer is a computer vision techique that takes two images - a content image and a style reference image—and blends them together so that the resulting output image retains the core elements of the content image, but appears to be “painted” in the style of the style reference image.
![image](https://user-images.githubusercontent.com/95982431/170819171-82078c18-e250-44bf-bdd7-8c78c7a04544.png)

In this repo I am going to use Inception Net V3 to create artistic images by combining different types of paintings also known as style images with different types of images also known as content images

# Content and Style Images

![image](https://user-images.githubusercontent.com/95982431/170818927-b74de356-a24a-4879-8adc-5789a38ecf6d.png)
![image](https://user-images.githubusercontent.com/95982431/170818953-305fed29-51ed-4bfa-998f-92e085d0d5d7.png)
![image](https://user-images.githubusercontent.com/95982431/170818971-e92fa5a9-a727-41a0-9641-58ebdfdea5e3.png)
![image](https://user-images.githubusercontent.com/95982431/170818976-cc089e83-21f7-4d44-a494-3d61fea2f023.png)

# Loss Functions
In Neural Style Transfer there are 3 types of loss functions that are calculated

- Style Loss
- Content Loss
- Total Loss

## Style Loss
The style loss is the average of the squared differences between the features and targets.
![image](https://user-images.githubusercontent.com/95982431/170819186-b7765aaf-f273-486c-b6bd-ff1dbb70e927.png)

## Content Loss
The content loss will be the sum of the squared error between the features and targets, then multiplied by a scaling factor (0.5).
![image](https://user-images.githubusercontent.com/95982431/170819290-96090d38-c857-4a42-8d22-a7d0de886588.png)

### Gram Matrix
Gram matrix is simply the matrix of the inner product of each vector and its corresponding vectors in same. It is used to calculate the style loss in neural style trasnfer. As you can see in the image below it is helps in calculation of the features of the generated image
![image](https://user-images.githubusercontent.com/95982431/170819347-0efdde53-7afd-4552-a442-5e5515e2969f.png)

## Total Loss
![image](https://user-images.githubusercontent.com/95982431/170819424-06ad68e0-09cb-4bdf-886a-188dccf2a034.png)





# Combined Images
![image](https://user-images.githubusercontent.com/95982431/170818814-e41280d1-dbf2-468b-a55b-513953ca6475.png)
![image](https://user-images.githubusercontent.com/95982431/170818870-ed2df403-a87f-49ac-b912-dd0ff06e442f.png)
![image](https://user-images.githubusercontent.com/95982431/170818867-9ce94ad4-d04b-4fe2-b9a5-0478b2c56283.png)
![image](https://user-images.githubusercontent.com/95982431/170818878-07d543cf-a4ea-49fc-be3b-7a3fbbfd3b92.png)

