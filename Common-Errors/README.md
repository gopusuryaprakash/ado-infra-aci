![TechSlate](../img/ts.png)

# <span style="color: lightgreen;">Common Error 1

### Below is the screenshot of the common error we get when we run infra pipeline. If we read the error message it is clearly asking use to register the Resource Provider in this case it is Container Instance. 

![Error](../img/error.png)


# <span style="color: skyblue;">How to solve this

## Step 1 : Navigate to Azure portal and click on subscription

![Azure1](../img/Azure1.png)

![Azure2](../img/Azure2.png)


## Step 2 : when you click on your subscription scroll down to left side options you will find Resource providers, click on that

![Azure3](../img/Azure3.png)

## Step 3 : Then search for container instance select that and click on register as shown below

![Azure4](../img/Azure4.png)

![Azure5](../img/Azure5.png)

## Step 4 : After finishing registration process refresh and then go on and run pipeline again

![Azure6](../img/Azure6.png)


# <span style="color: lightgreen;">Common Error 2

### Below is the screenshot of the common error2 we get when we run infra pipeline. This is because as the dns name should be unique you need to change the name before running pipeline.

![Error2](../img/error2.png)


### If you see below image it is clearly mentioned in comment to change dns name in vars.tf



![Error2-sol](../img/Error2-sol.png)
