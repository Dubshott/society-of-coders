---
title: 'Different Types of Computing'
date: '06-03-2021'
class: 'CSP'
section: 4 
author: 'Abhijay Deevi'
---

There are three main types of computing. Sequential, Parallel, and Distributed. The one you choose determines how long a computer will process something.

First, there is sequential computing. This means that one task is done after another. This is a very slow method of completing the tasks. Most people will choose Parallel or Distributed because it completes the task like the sequential but much faster. The only reason somebody would use sequential computing is when their computer's CPU (Central Processing Unit) is outdated. It also depends on how heavy the task is on the load. Notice in the picture how everything has to go through a solid line and do one task after the other which is taking a lot of time. 
  
<p align="center">
  <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.codenomads.nl%2Fwhen-flow-split-an-introduction-to-concurrent-programming%2F&psig=AOvVaw3mo-YJXeZFeyXWXu1wdFK_&ust=1623439490807000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJDousPljfECFQAAAAAdAAAAABAk" />
<p>

Next, there is parallel computing. What this does is it breaks the program into multiple smaller sequential computing operations so that multiple tasks can be done at the same time. This is much more efficient than the sequential computing method and will finish the program in a shorter amount of time. People will be able to do this if their CPU and GPU (Graphics Processing Unit) is faster. This is also more data driven and the solutions can scale more effectively than sequential. Notice in this picture how this huge problem is being split up into smaller tasks so the time it takes to complete it is much less. 
  
<p align="center">
  <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.omnisci.com%2Ftechnical-glossary%2Fparallel-computing&psig=AOvVaw0BipoSpqP8u3YFgolYMP_3&ust=1623439568549000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCLCS7-jljfECFQAAAAAdAAAAABAD)" />
<p>

Now Collegeboard mostly just compares Parallel computing and Sequential Computing. Distributed computing is just something you should know, but it probably won't appear on the test. 

If we want to compare both of them we need to do these things:
Sequential: Add up all the times for each individual task. 
Parallel: Time is the longest time taken on any given processor.

Since there are multiple parts working on the task for a parallel solution, the time it takes for the program to complete must just be the longest time for one part. 

For these types of questions, Collegeboard will usually give you a table and ask you something like "How much longer does a sequential process take compared to a parallel process?"
Then you use the ideas above, add up the times it will take and see the difference. 

Finally, there is distributed computing. This is a little different from parallel processing. Distributed computing still completes multiple tasks at the same time but instead of doing it on just one computer, it will completely with more than 1 physical computer. This is a little more annoying because it also requires network. Also, since there are multiple devices, it might take longer than a parallel execution because of the network and/or the amount of time it takes to recieve a response from the other computers. Notice in this picture how the main computer is splitting that task and placing them into 4 other computers. 
  
<p align="center">
  <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.khanacademy.org%2Fcomputing%2Fap-computer-science-principles%2Falgorithms-101%2Fx2d2f703b37b450a3%3Aparallel-and-distributed-computing%2Fa%2Fdistributed-computing&psig=AOvVaw2uWkN1laENulPcazwb6MyQ&ust=1623439600150000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMjqlvvljfECFQAAAAAdAAAAABAD" />
<p>

This means that distributed computing is a mix since the time it takes to complete all the tasks is in the middle of of the other two types. 

Just remember this: Sequential < Distributed < Parallel in terms of speed.

If you want more information on this then look at Big Idea 4 on Collegeboard. It is the 3rd topic. 
