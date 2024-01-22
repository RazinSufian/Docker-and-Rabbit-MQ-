# Rabbit MQ Massage Broker

### Install Rabbit MQ

```bash
sudo apt update
sudo apt upgrade
```

[https://lh7-us.googleusercontent.com/UYYCVihxVtWFHuExeJR57nH4ILk-sixNAGCGxeAMmA3OhMnmiVKMHqH9qSrHQZ4s4KFSb_Ks4r1dLpcjM-AEm4b4voq42ADAUsLQLpypsrXLIrZBhJJsTJc9K5HeumeyXo5P2xuetH8zE0I-E2H29I8](https://lh7-us.googleusercontent.com/UYYCVihxVtWFHuExeJR57nH4ILk-sixNAGCGxeAMmA3OhMnmiVKMHqH9qSrHQZ4s4KFSb_Ks4r1dLpcjM-AEm4b4voq42ADAUsLQLpypsrXLIrZBhJJsTJc9K5HeumeyXo5P2xuetH8zE0I-E2H29I8)

### **Install Erlang:**

RabbitMQ requires Erlang to be installed. I can install it using the following steps:

a. Add the Erlang repository:

```bash
wget -O- https://packages.erlang-solutions.com/ubuntu/erlang_solutions.asc | sudo gpg --dearmor -o /usr/share/keyrings/erlang-solutions-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/erlang-solutions-archive-keyring.gpg] https://packages.erlang-solutions.com/ubuntu $(lsb_release -cs) contrib" | sudo tee /etc/apt/sources.list.d/erlang-solutions.list
```

[https://lh7-us.googleusercontent.com/E2ZJD0R2IDeNRitOlCC0FFziHUeGFtW_f8gw_QYa2kSCy-9JjII-EOVPQUwoQImW3MD54Sf00HllqlID9DYn_HuRX4WinF6olPg9RmT0CSMEMNC2jSYNvCHxlq6tTD2FFEMhyGwUahh_YG1QoXOIDi8](https://lh7-us.googleusercontent.com/E2ZJD0R2IDeNRitOlCC0FFziHUeGFtW_f8gw_QYa2kSCy-9JjII-EOVPQUwoQImW3MD54Sf00HllqlID9DYn_HuRX4WinF6olPg9RmT0CSMEMNC2jSYNvCHxlq6tTD2FFEMhyGwUahh_YG1QoXOIDi8)

b. Update my package list and install Erlang:

[https://lh7-us.googleusercontent.com/2RzO2Ni7Ffpl6UV33zIbn-Z0CVE0OUtr2PoA95f6gKTKaB2x4QviEC4An9Sz_Cpx4arqQbnxuoLJAhZ_hZtc58DBj91lG7NeFFEilplgpnM2ea9qpdvs-HMiw4Yc3acW7Hyt110QU6QGc5x0ETjpZgk](https://lh7-us.googleusercontent.com/2RzO2Ni7Ffpl6UV33zIbn-Z0CVE0OUtr2PoA95f6gKTKaB2x4QviEC4An9Sz_Cpx4arqQbnxuoLJAhZ_hZtc58DBj91lG7NeFFEilplgpnM2ea9qpdvs-HMiw4Yc3acW7Hyt110QU6QGc5x0ETjpZgk)

[https://lh7-us.googleusercontent.com/GVw2-3HpSe65UKOHrR1SLOUFHdfRhQdoMylZEnPslhWL4k2IP01CPWs4jVMcadn1m_jsNIkTxy40yZdoa2H9H64EZlEzC-HFECi4EB58zpJ44jAuRGvTSG9BLZOAhPKgCPQ05rqLji4tpuPFllRlxJM](https://lh7-us.googleusercontent.com/GVw2-3HpSe65UKOHrR1SLOUFHdfRhQdoMylZEnPslhWL4k2IP01CPWs4jVMcadn1m_jsNIkTxy40yZdoa2H9H64EZlEzC-HFECi4EB58zpJ44jAuRGvTSG9BLZOAhPKgCPQ05rqLji4tpuPFllRlxJM)

### **Install RabbitMQ:**

With Erlang installed, I can now install RabbitMQ:

a. Add the RabbitMQ repository to my system:

```bash
wget -O- https://github.com/rabbitmq/signing-keys/releases/download/2.0/rabbitmq-release-signing-key.asc | sudo gpg --dearmor -o /usr/share/keyrings/rabbitmq-archive-keyring.gpg
```

```bash
echo "deb [signed-by=/usr/share/keyrings/rabbitmq-archive-keyring.gpg] https://packagecloud.io/rabbitmq/rabbitmq-server/ubuntu/ $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/rabbitmq.list
```

[https://lh7-us.googleusercontent.com/Pyf6-r_G8iS6f-MTiaBunLhGbbMm1ejNAyebVt4jzz3K9IOh5-MZCmBRD9ZNmgq4K4XixGsJN4gytysoXmD-7MGYn1nSZh1iirLY_3beZNSk_ngsoTrwhw4jFD-Gwz6xk-5oaBziAkvqkk7utu8Fj_g](https://lh7-us.googleusercontent.com/Pyf6-r_G8iS6f-MTiaBunLhGbbMm1ejNAyebVt4jzz3K9IOh5-MZCmBRD9ZNmgq4K4XixGsJN4gytysoXmD-7MGYn1nSZh1iirLY_3beZNSk_ngsoTrwhw4jFD-Gwz6xk-5oaBziAkvqkk7utu8Fj_g)

b. Update my package list again:

```bash
sudo apt update
```

[https://lh7-us.googleusercontent.com/SUFD4WWMnJ5TtIvV-lQnRR-DXjJy74ThPf9bd0I9Rs6kT8WPObp8VR08b-lie51I3IcFvi-lP-7GF2h5bft5uT1KzQZXSTTRqwn-M6zfRvTxjIXVpj7LvCGHOv6FeakJpMBBunhmD1GDv37CkI2yCSU](https://lh7-us.googleusercontent.com/SUFD4WWMnJ5TtIvV-lQnRR-DXjJy74ThPf9bd0I9Rs6kT8WPObp8VR08b-lie51I3IcFvi-lP-7GF2h5bft5uT1KzQZXSTTRqwn-M6zfRvTxjIXVpj7LvCGHOv6FeakJpMBBunhmD1GDv37CkI2yCSU)

c. Install RabbitMQ server:

```bash
sudo apt install rabbitmq-server
```

[https://lh7-us.googleusercontent.com/uIGQafUZke_oBMhHHp9q5Ls4hcIpbRpaE5CodUTEzzFS-XqRBlvPDHuAsUyscKhd-rz9zP8DGhXfb5sB4OJ2MqK-b_FA-Cw6tOIOnoDVIWqnPrwRPOCJv5vFYUYsZoyu4K-Zbz2PapcP0XcqRSZ4U_8](https://lh7-us.googleusercontent.com/uIGQafUZke_oBMhHHp9q5Ls4hcIpbRpaE5CodUTEzzFS-XqRBlvPDHuAsUyscKhd-rz9zP8DGhXfb5sB4OJ2MqK-b_FA-Cw6tOIOnoDVIWqnPrwRPOCJv5vFYUYsZoyu4K-Zbz2PapcP0XcqRSZ4U_8)

**Start and Enable RabbitMQ Service**

Once installed, I need to start the RabbitMQ service and enable it to start on boot:

```bash
sudo systemctl start rabbitmq-server
```

```bash
sudo systemctl enable rabbitmq-server
```

[https://lh7-us.googleusercontent.com/Tuyu9FRSfQhdx9C9auxQ7Ccwa1fsK32Z54QwwWODaE5bXGNZ7cgIhQMIHIISgo00WDnOtecPixZPPlIX_Mj6fqPj0DFVldrtH2el4aAU5ES68Q6ap9uGYCXkfN3D1klQY-UE7Go--C4ydpw2ITGwwVk](https://lh7-us.googleusercontent.com/Tuyu9FRSfQhdx9C9auxQ7Ccwa1fsK32Z54QwwWODaE5bXGNZ7cgIhQMIHIISgo00WDnOtecPixZPPlIX_Mj6fqPj0DFVldrtH2el4aAU5ES68Q6ap9uGYCXkfN3D1klQY-UE7Go--C4ydpw2ITGwwVk)

**Check RabbitMQ Status:**

To verify that RabbitMQ is running correctly, using the following command:

```bash
sudo systemctl status rabbitmq-server
```

[https://lh7-us.googleusercontent.com/RMZXNyC7-UUpGR1_qX5Jj1tetj1F3UTw_yjQvxEtoy86o3gCn2E8Tfb6g3bzz9otA01DNdIcvi1-oB7OppoEo48MAsEoHjxoV2bHPVPYYauBGjaS3NrjngL6AQ-_EzIA9GpeUZ070JNV9tF1xRvZahI](https://lh7-us.googleusercontent.com/RMZXNyC7-UUpGR1_qX5Jj1tetj1F3UTw_yjQvxEtoy86o3gCn2E8Tfb6g3bzz9otA01DNdIcvi1-oB7OppoEo48MAsEoHjxoV2bHPVPYYauBGjaS3NrjngL6AQ-_EzIA9GpeUZ070JNV9tF1xRvZahI)

**Install python and pike:**

**Install Python 3 and Pip**

```bash
sudo apt install python3
```

```bash
sudo apt install python3-pip
```

[https://lh7-us.googleusercontent.com/5nPzX6PemricexSxgW-anatG1LdJ6IdikYETwS5P3a_fxp352WrFm659vvizKEOPUJeguiwAd41kUiGX6t8EpUO2ZoNVOFDJOdOPvOv3Vbqv62HfOwacOGLfCOy0zcOQCZeUgipy41XLS-r7w4XuN-Y](https://lh7-us.googleusercontent.com/5nPzX6PemricexSxgW-anatG1LdJ6IdikYETwS5P3a_fxp352WrFm659vvizKEOPUJeguiwAd41kUiGX6t8EpUO2ZoNVOFDJOdOPvOv3Vbqv62HfOwacOGLfCOy0zcOQCZeUgipy41XLS-r7w4XuN-Y)

**Python version check:**

python3 --version

[https://lh7-us.googleusercontent.com/A2jq_o7_nLZW15lWmXRWOqNvXbUic41WT2n1GsO03tMz3BOhw9ROd30rvIlesMKyoLRK6B81G4T1U_0d3QkKo6bq_XwhEsrMciKCT3ACH7A6AivF0s_AD8X-5StoZCTa3V85YWcFuHMJ9SK0P2FhM7M](https://lh7-us.googleusercontent.com/A2jq_o7_nLZW15lWmXRWOqNvXbUic41WT2n1GsO03tMz3BOhw9ROd30rvIlesMKyoLRK6B81G4T1U_0d3QkKo6bq_XwhEsrMciKCT3ACH7A6AivF0s_AD8X-5StoZCTa3V85YWcFuHMJ9SK0P2FhM7M)

**Install Pika:**

Once I have confirmed that Python is installed, I can proceed to install Pika, which is a RabbitMQ client library for Python. I can do this using pip, Python's package manager.

Since I am using Python 3, I will use pip3. Here is the command to install Pika:

```bash
pip3 install pika
```

[https://lh7-us.googleusercontent.com/TkcyWXM_QNCmcxQdzOeWPtmTGG6rx-s6Am_DiInlvqx2Dv2heKbS2YT0i6Fns-a3ANAoMVaLygflxSz6df5-bOZXimO3fR0bww1I3Es-XeHxW8xIhiwCSHI0uC4x8v7UfkDAcV6FTrWYqi_1lLT-PKI](https://lh7-us.googleusercontent.com/TkcyWXM_QNCmcxQdzOeWPtmTGG6rx-s6Am_DiInlvqx2Dv2heKbS2YT0i6Fns-a3ANAoMVaLygflxSz6df5-bOZXimO3fR0bww1I3Es-XeHxW8xIhiwCSHI0uC4x8v7UfkDAcV6FTrWYqi_1lLT-PKI)

**Verify Pika Installation:**

```bash
pip3 show pika
```

[https://lh7-us.googleusercontent.com/3jKHOf4AGnAMKoivxCZJ9GQdJTT9UO3Y2qgIlvyCbj1kB1D7VV_pHqsQdz6hEWoJ1l7x93SI7DxIT1xjJrRw9Tjf_t7qvOZJ6NLEWyMYGSycnoVmdrY0GfnPeAhbElQEa_dTjqLeJYzsxgUpbQssFdE](https://lh7-us.googleusercontent.com/3jKHOf4AGnAMKoivxCZJ9GQdJTT9UO3Y2qgIlvyCbj1kB1D7VV_pHqsQdz6hEWoJ1l7x93SI7DxIT1xjJrRw9Tjf_t7qvOZJ6NLEWyMYGSycnoVmdrY0GfnPeAhbElQEa_dTjqLeJYzsxgUpbQssFdE)

**Task 1:**

### Creating a producer and a consumer script using pika:

Create a file `[producer.py](http://producer.py)` using a text editor. In this case I am using my default text editor neovim.

```bash
nvim [producer.py](http://producer.py/)
```

Then write this code in the file:

```bash
import pika

# Connect to RabbitMQ server (assuming it's running on localhost)
connection = pika.BlockingConnection(pika.ConnectionParameters('localhost'))
channel = connection.channel()

# Declare a queue named 'hello' where the message will be sent
channel.queue_declare(queue='hello')

# Send a message
message = "Hello, RabbitMQ!"
channel.basic_publish(exchange='', routing_key='hello', body=message)

print(" [x] Sent 'Hello, RabbitMQ!'")

# Close the connection to RabbitMQ
connection.close()
```

[https://lh7-us.googleusercontent.com/xAKfUw_aXUuXOQ7KMJwaOelUaK_XfDhuV3M5vAiEJ91lyheEB0UHwOQGJsb2LuPV0MyaAC-aB2Bu54OL06Mc2FoiAKUcjser_d36YFkKY6GaJ8TyXPXAs-gfLKqDExw-0WdKf1ADhIPbAESrx3c1jAw](https://lh7-us.googleusercontent.com/xAKfUw_aXUuXOQ7KMJwaOelUaK_XfDhuV3M5vAiEJ91lyheEB0UHwOQGJsb2LuPV0MyaAC-aB2Bu54OL06Mc2FoiAKUcjser_d36YFkKY6GaJ8TyXPXAs-gfLKqDExw-0WdKf1ADhIPbAESrx3c1jAw)

**Step 3: Run the Consumer Script**

Now, let us create another file `consumer.py` using the same method:

```bash
nvim [consumer.py](http://consumer.py/)
```

```bash
import pika

# Connect to RabbitMQ server (assuming it's running on localhost)
connection = pika.BlockingConnection(pika.ConnectionParameters('localhost'))
channel = connection.channel()

# Declare the same queue as in the producer
channel.queue_declare(queue='hello')

# Define a callback function to handle received messages
def callback(ch, method, properties, body):
    print(" [x] Received %r" % body)

# Consume messages from the 'hello' queue with the callback function
channel.basic_consume(queue='hello', on_message_callback=callback, auto_ack=True)

print(' [*] Waiting for messages. To exit, press CTRL+C')
channel.start_consuming()
```

I'll open a terminal window.

Run the Consumer:

In the terminal, I'll run the script by typing:

```bash
python3 receive.py
python3 consumer.py
```

[https://lh7-us.googleusercontent.com/kwIZvT2dt0rhpkl3C9dJEDVRHNW3d6EhKXu6KSEFM6qnNgT2e5z57Wv1t9avlCls85ymQhltvP1XuZ-7jgF-XKWjAJKdnwhVlWBMffLAFuKZHloDaNvadh-r5GSbFFY0u_3xyamY2yw3Y9_ECL8fklc](https://lh7-us.googleusercontent.com/kwIZvT2dt0rhpkl3C9dJEDVRHNW3d6EhKXu6KSEFM6qnNgT2e5z57Wv1t9avlCls85ymQhltvP1XuZ-7jgF-XKWjAJKdnwhVlWBMffLAFuKZHloDaNvadh-r5GSbFFY0u_3xyamY2yw3Y9_ECL8fklc)

**Step 4: Run the Producer Script**

I'll open a new terminal window to run the producer script.

Run the Producer:

In the new terminal, I'll type:

```bash
python3 send.py
```

[https://lh7-us.googleusercontent.com/aGmuvfKLmNdDSBMypnUmURW-pCHKTNPODa4lCPbsl69YiAiL9YvVWljwbFF0eDjqI_1bpRtsbYtlU8VwMafG8GXMe57XWLAb39_ez-4dbWNYMP6SDncOldNnAHzmg3I4sJrIs_FtvyN0C8jmlJUDvU0](https://lh7-us.googleusercontent.com/aGmuvfKLmNdDSBMypnUmURW-pCHKTNPODa4lCPbsl69YiAiL9YvVWljwbFF0eDjqI_1bpRtsbYtlU8VwMafG8GXMe57XWLAb39_ez-4dbWNYMP6SDncOldNnAHzmg3I4sJrIs_FtvyN0C8jmlJUDvU0)

**Step 5: Observe the Output**

In the terminal where I ran receive.py, I should see the message " [x] Received 'Hello World!'".

In the terminal with send.py, I'll see " [x] Sent 'Hello World!'" confirming the message was sent.

[https://lh7-us.googleusercontent.com/PMn7x3jm0wHW8D0vnscfk4VYqDQSymILBhbqM2w1QM3-SwXZBw4z9CVeJH-rvZP-xh0_t0mQbGSfvDYCjLtGdbFaQ9uJ3CHPCw2tprK1ZOz8CGN8Yh380eb6RZR8cBlv541eoV8pwkrJB9IldL9O-E0](https://lh7-us.googleusercontent.com/PMn7x3jm0wHW8D0vnscfk4VYqDQSymILBhbqM2w1QM3-SwXZBw4z9CVeJH-rvZP-xh0_t0mQbGSfvDYCjLtGdbFaQ9uJ3CHPCw2tprK1ZOz8CGN8Yh380eb6RZR8cBlv541eoV8pwkrJB9IldL9O-E0)

## TAKS2: Work queues

To complete Task 2, "Work Queues," using RabbitMQ, we will create a task sender script and a worker script that processes tasks with varying complexities.

### **Create the Task Sender Script:**

Lets write a python script `new_task.py` that will send messages simulating tasks with various processing time.

```bash
nvim new_task.py
```

```bash
import pika
import sys

connection = pika.BlockingConnection(pika.ConnectionParameters('localhost'))
channel = connection.channel()

channel.queue_declare(queue='task_queue', durable=True)

message = ' '.join(sys.argv[1:]) or "Hello World!"
channel.basic_publish(
    exchange='',
    routing_key='task_queue',
    body=message,
    properties=pika.BasicProperties(
        delivery_mode=2,  # make message persistent
    ))

print(f" [x] Sent {message}")
connection.close()
```

**Step 2: Create the Worker Script**

I'll create a new file in my text editor for the worker script.

```bash
nvim worker.py
```

Write the Worker Code: This script will pick up tasks from the queue and simulate processing them. The code will be:

```bash
import pika
import time

connection = pika.BlockingConnection(pika.ConnectionParameters('localhost'))
channel = connection.channel()

channel.queue_declare(queue='task_queue', durable=True)

def callback(ch, method, properties, body):
    print(f" [x] Received {body}")
    time.sleep(body.count(b'.'))
    print(" [x] Done")
    ch.basic_ack(delivery_tag=method.delivery_tag)

channel.basic_qos(prefetch_count=1)
channel.basic_consume(queue='task_queue', on_message_callback=callback)

print(' [*] Waiting for messages. To exit press CTRL+C')
channel.start_consuming()
```

I'll save this file as worker.py.

[https://lh7-us.googleusercontent.com/AmbUVSsS7O0iy93o2a8XUDHmVH8CIHN0kr56bxlLL10stAnUePfFhlGKPU3rN1BlBHYa4hNJXfwDI0xM2GHMI_9qD5-cJECMb-hXQWsxOYb7XG_YKDyKTv4fJu-PgbozmK9mKcmWfVXCeIAHJi6XGOI](https://lh7-us.googleusercontent.com/AmbUVSsS7O0iy93o2a8XUDHmVH8CIHN0kr56bxlLL10stAnUePfFhlGKPU3rN1BlBHYa4hNJXfwDI0xM2GHMI_9qD5-cJECMb-hXQWsxOYb7XG_YKDyKTv4fJu-PgbozmK9mKcmWfVXCeIAHJi6XGOI)

**Step 3: Run the Worker Script**

Open Terminal: I'll open a new terminal window.

Run the Worker: In the terminal, I'll run the script by typing:

```bash
python3 worker.py
```

I'll repeat this step to open multiple worker instances in different terminals.

[https://lh7-us.googleusercontent.com/wckOeYmYR0wVzdxgzv61hTVkQMJx0G19ksDrt0u8chUhwiwXybBl-QvTL1vFEfJiy94Gn6mot5SyT9OAiyZdxeGGyWIvEykls2QPwhWdohtDa-wFWAF18ZPEBvFPVo44Pw8XD_JJSvl0Kg3fxI30zwE](https://lh7-us.googleusercontent.com/wckOeYmYR0wVzdxgzv61hTVkQMJx0G19ksDrt0u8chUhwiwXybBl-QvTL1vFEfJiy94Gn6mot5SyT9OAiyZdxeGGyWIvEykls2QPwhWdohtDa-wFWAF18ZPEBvFPVo44Pw8XD_JJSvl0Kg3fxI30zwE)

Actions and Observations:

In my demonstration of RabbitMQ's work queue distribution, I initially set up three instances of worker.py, each in a separate terminal window, arranged on my screen from top to bottom in the order they were launched. This setup was intended to showcase how RabbitMQ distributes tasks among different workers.

Next, I opened a new terminal to serve as the task sender. Here, I executed the new_task.py script with various commands to simulate tasks of different lengths, such as python3 new_task.py TaskA.., python3 new_task.py TaskB..., and so forth, creating a series of tasks labeled from TaskA to TaskF, each with an increasing number of dots indicating longer processing times.

Observing the worker terminals, I noticed the distribution of tasks among them. The first worker (top terminal) processed 'TaskA..' and 'TaskD..', the second worker (middle terminal) handled 'TaskB..' and 'TaskE..', and the third worker (bottom terminal) took on 'TaskC..' and 'TaskF..'. This pattern effectively demonstrated RabbitMQ’s load balancing capability, where tasks were evenly distributed among the available workers.

Through this exercise, I gained insights into how RabbitMQ manages task queues, ensuring an equitable distribution of workloads across multiple workers, which is pivotal in managing large-scale, distributed applications.