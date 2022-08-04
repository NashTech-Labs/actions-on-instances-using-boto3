## Start , Stop , Reboot and terminate instances using boto3

The python script in this template will help you perform four operations on instances in AWS.

1 - Start instance

2 - Stop instance

3 - Reboot instance

4 - Terminate instance.

The script recognizes the instance using the instance id.So it becomes easy to directly perform the operations using the terminal and not going on aws console again and again.





**Files:**

```python
    start-stop-reboot-terminate.py
   
```

## How to run the above script.

1. First configure the aws credentials on whatever machine you want to run the script by running the below command.

   The profile name in the below configuration will be used in the script and the region should be same wherever the instance is running

   ```
    aws configure
   ```

2. Now, from the current directory run the following command to validate the script.

   ```python
    python3 start-stop-reboot-terminate.py
   ```