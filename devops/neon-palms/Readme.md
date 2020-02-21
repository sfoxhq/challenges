The digital palm tree market is booming and Neon Palms LLC is experiencing a surge in demand for its three digital trees:

<img src="palm-1.jpeg" alt="palm-1.jpeg" width="100" style="margin-right: 50px">
<img src="palm-2.gif" alt="palm-2.gif" width="100" style="margin-right: 50px">
<img src="palm-3.jpg" alt="palm-1.jpeg" width="100" style="margin-right: 50px">

# Part 1
Spin up a multi-node kubernetes cluster on an AWS free tier account. Do not use Amazon EKS.

# Part 2
Deploy a group of web servers into the cluster where each server may only serve one of the three digital trees. Ensure that your solution is capable of handling outages.

# Part 3
Once you're up and running, use `kubectl` to describe each of the intermediary kubernetes objects that link a Service to the Pod serving palm-2.gif. Demonstrate how each are linked.

# Part 4
Using `kubectl`, describe how the pod serving palm-1.jpeg can communicate with palm-3.jpg should they land on separate hosts.
