The Notebook ' StyleTransfer_Promit.ipynb' contains the code for Neural Style Transfer.

To run the notebook, just upload it to Google Colab and execute the cells.
My notebook (Public):
https://colab.research.google.com/drive/19ceTN1pUuwdtAQBamock0D83NUG6adzd?usp=sharing

Libraries Used/ Requirements:

1. Pillow 
2. tensorflow
3. numpy 
4. matplotlib
5. opencv-python


**Evaluation on results obtained from stylizing with *The Starry Night by Vincent van Gogh, 1889*.**

![image](https://github.com/PromitHal/PromitAssign/assets/83832850/802afa8b-5811-407c-9c9b-8b0de55d0749)

| Image             | Content Loss | Style Loss | Visual Appeal |
|-------------------|--------------|------------|---------------|
| Dzukou Valley, Nagaland | 3.25e-6     | 174.05     | Okayish       |
| Darjeeling        | 4.5e-6       | 130.89     | Good enough   |
| Wakhaba Falls     | 2.79e-6      | 80.07      | Good enough   |
| Dawki River       | 1.87e-6      | 91.5       | Nice one      |


**Evaluation on results obtained from stylizing with A painting by Pablo Picasso**

![image](https://github.com/PromitHal/PromitAssign/assets/83832850/eb8655ad-71c8-4052-9c5b-82445f4f0643)


| Image             | Content Loss | Style Loss | Visual Appeal |
|-------------------|--------------|------------|---------------|
|  1                | 1.5e-6       | 100.05     | Nice          |
|  2                | 2.73e-6      | 90.89      | Nice          |
|  3                | 5.974e-6     | 69.36      | Nice          |
|  4                | 1.67e-6      | 70.58      | Nice          |

1. For the first painting (The Scary Night by Van Gouge) the results are not very visually appealing, whereas for the second style ( A painting by Pablo Picasso), the results are much better.
2. This is quantified by the lower loss values (both content and style loss) in the second case. The stylized images are more visually appealing in the second case.

   
