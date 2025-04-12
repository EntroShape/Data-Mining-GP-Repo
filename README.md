# Cityu-Data-Mining-GroupProject-Repo

In this data mining group project, we performed the data mining task of walmart sales prediction on the Walmart.csv dataset from kaggle (https://www.kaggle.com/datasets/yasserh/walmart-dataset), here is the required public repository that store the source code, docs, and datasets used. All the code and experiment that we used are already stored in the file called "DataMiningV22(version_finale) (1)". Below is two notes for running our code.

## Best Pratice to Run the Code 
### Step 1 : Download the code and dataset from this repo (_Dont rename the dataset!_)
### Step 2 : Open the google colab on web browser and login 
![image](https://github.com/user-attachments/assets/1c888e04-01a0-468c-bd31-6c266616a4bb)
### Step 3 : Click the upload button and drag the "DataMiningV22(version_finale) (1)" file
![image](https://github.com/user-attachments/assets/c3335f07-a6e0-4638-acb0-8ae6dd98e4a0)
### Step 4 : Upload the data file 
Click this button inside the red circle
![image](https://github.com/user-attachments/assets/e32313aa-0b78-4c89-b173-8647b6b8b792)
Click this button inside the red circle
![image](https://github.com/user-attachments/assets/baa3cc81-a3d6-4e82-991c-fd9246aab513)
Click the data file name "Walmart.csv"
![image](https://github.com/user-attachments/assets/3643ce90-8e99-4ec9-8820-f5e21c08d3f9)
Now Back to the google colab, after waiting a few second, the "Walmart.csv" should now be able to seen
![image](https://github.com/user-attachments/assets/fdb588cd-f590-4773-92fa-b2661b8bcb42)
### (Optional) Step 4.5 : Use the GPU Provided by google free of charge
Since our experiemnt include Transformers and Informers, altough the epoch is small, but it would still be time consuming to run the experiment using the CPU.
Hence, we can use the GPU resource provided by google to accelerate our experiemnt.

First, click the runtime button on the top bar as shown in the figure.
![image](https://github.com/user-attachments/assets/e6e58425-a3cf-48cf-9e7d-2cf02c49d5f5)
Second, you can see that our default setting is CPU, we can change the runtime to T4 GPU
![image](https://github.com/user-attachments/assets/8868b55b-ff8c-4b85-aa40-3e192c2b1452)

### Step 5 : Run the code

Cick the runtime button on the top bar, then click run all.

![image](https://github.com/user-attachments/assets/77e3dc12-834a-4322-8dcf-e96f4ca9e08f)


After these five easy step, you should be able to run the code easily

## Restart the session Problem
Due to the potential re-installation of numpy, when you run the code, there might be a sudden pop-up box that ask you to restart the session.
![image](https://github.com/user-attachments/assets/44bd3099-1d4b-4d55-9266-fe07e8378f18)
This is not an error, you can simply click the "restart session", and click the run all agian, then the code should be able to run free of bug and generate all the result and graph that shown in the report.
