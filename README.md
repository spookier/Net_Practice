# How Networking Was Born


  
## Networking

If you want your computer to talk to another computer (share data), you would want to use an ethernet cable to connect to that computer. 


<div align="center">
  
![01](https://github.com/spookier/Net_Practice/assets/77325667/9ebeb80e-2e0b-44d8-b7be-9090b1eacade)

</div>


But what if a third PC would want to connect as well ?

That’s where switches come in.


## Switches

If a third PC wants to connect, instead of digging a new ethernet port in each PC and plug an ethernet cable between each PC, you can just use a **switch.** 


<div align="center">

*Here’s an exact representation of what you would feel if you had to connect 5 PCs without a switch*
  
![02](https://github.com/spookier/Net_Practice/assets/77325667/ebf31f68-78ca-4afa-9346-3ff5b135e1e0)

</div>

### So what is a switch ?

A switch allows multiple devices to connect and communicate with each other, creating a central hub.

Switches allows two or more IT devices (PC, Printers, Security Cameras, Servers…) to communicate with one another. 

In short, they let other IT devices connect together.

<div align="center">
  
![03](https://github.com/spookier/Net_Practice/assets/77325667/65319ec2-01cb-4632-91ec-873d915e42b4)

</div>

This entire setup of IT devices + a switch is called **a network**.

But even then, there’s a limit on how many devices a switch can handle.

The ASICs (an ASIC is a type of chip that is designed to do a specific task very efficiently) and the CPU of a switch have a limit on how many tasks per connection they can handle.

So if you were to connect a sixth PC to a switch that is only designed to handle five, you would experience performance degradation.

To mitigate this, you would introduce **an additional switch** into the network and distribute the PCs between them. This effectively creates a second network, also called **a** **subnetwork**.

By creating this additional subnetwork, you're distributing the traffic that would otherwise overload a single 5-port switch when connecting six, seven, or even eight PCs.

<div align="center">
  
  ![04](https://github.com/spookier/Net_Practice/assets/77325667/049babe3-eb49-471b-abfc-d4210c6bc92b)

</div>

But here, another problem arises… 

How does a PC on the original network communicate with a PC on the newly established subnetwork?

That is through routers.

## Routers

To overcome the limitation of switches and enable the communication between multiple networks, (*in our case the original network and our subnetwork*) routers are used. 

A router is a device that connects different networks and allows data to be transferred between them. It acts as a central hub for connecting networks.

Think of a router like a traffic cop for computer networks. It helps direct information to the right place.

So, if a computer on our first network wants to talk to a computer on the second network, it asks the router to help send its message to the right computer.

<div align="center">
  
![05](https://github.com/spookier/Net_Practice/assets/77325667/25de1501-39d7-4ed7-a2a8-104161492ae3)


</div>

## The Internet

So now take this concept and x1000 it. This is what “the internet” really is.

It is a giant web of many devices and switches all over the world, with lots of "traffic cops" making sure information gets where it needs to go.

<div align="center">
  
![06](https://github.com/spookier/Net_Practice/assets/77325667/ba06ad6c-5d8d-4f3f-a593-3fa59dac1bc1)

</div>

---

## The Handy Box

But these days, for most people at home, you don't need separate devices like that anymore.

Instead, what you often have is, a single box called a "router".


<div align="center">
  
![image](https://github.com/spookier/Net_Practice/assets/77325667/28ee6392-7649-49aa-99d6-25f6e34ac311)

</div>


And beneath this “router”, it's actually the 2 different components that I had just explained to you plus one I left out, the WAP.

The WAP acts basically as a wireless switch.

1. **The Router**: Send your data to other networks, like the internet.
2. **The Switch**: Connect several wired devices in your home network, allowing them to communicate with each other.
3. **A Wireless Access Point (WAP)**: Lets wireless devices like phones and laptops connect to your network without cables.

So instead of having a separate switch with lots of ports and a separate router to manage traffic between your home network and the internet, you have this one handy package that does it all. 

If you had a big company with lots of devices, you might need a bigger, separate switch and more advanced routing equipment, that’s why they need network engineers.
