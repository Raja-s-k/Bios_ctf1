
![image](https://user-images.githubusercontent.com/92567732/176679019-17a662e8-60fc-405d-93bc-964d818fdf90.png)


&nbsp;
&nbsp;

# Indy_CTF writeups

&nbsp;

## Hardware

### Noice_UART

#### Description

Can you decode it?


#### Solution

When I first looked at the question I doubted that may be in binary form. So, just to give
it a try I searched for binary to text converter online I found this website < [link](https://www.rapidtables.com/convert/number/binary-to-ascii.html) >
Then i typed the given input as as shown below 

![Binary to text ](https://1drv.ms/u/s!AmLU-HRApSaSgaUcq31EtHN3To1JDw?e=hqqfQX)

![Screenshot 2022-06-29 192410](https://user-images.githubusercontent.com/92567732/176455051-3622da73-3f12-44ed-86b3-8e5277552f56.png)


#### Flag

The flag which i got is ictf{R128ASB}


### Hello_Hardware

### Description

Can yu make the output high?

### Solution

I implemented the concept of **reverse engineering** i.e., I examined the circuit from **last to first**.
 On seeing the circuit first time I thought it is some what complicated. But even though I started to solve the circuit.
 Imessed some where while solving it for the first time. I got the value of **A B C D as 1 0 0 1** while solving it second time.
I gave the same to the [virtual hardware](https://wokwi.com/projects/334568130647949906) and got 
the correct flag.

### Flag

I got the flag as ictf{G00d_woRk}


## Wireless 

### Dots&Dashes

### Description

Decrypt the audio to find the flag!!

### Solution

 To solve this CTF challenge i downloaded the audio file and just use [morse decoder](https://morsecode.world/international/decoder/audio-decoder-adaptive.html).

 **DECRYPTED STRING: **IEIIEIEINTEIÞSDIFTEEITIISDISNENASITIEETTTTTAECC**ICTF R1CKR0113DONMRS3**

I found the ictf flag in the here but a letter "o" is not in caps. So, I changed
it to caps and submitted the flag.

### Flag

The flag i got is ICTF{R1CKR0113DONMRS3}


### murphy's ghost

### Description

Decipher the ciphertext

### Solution

On reading the description it is clear that the qn is something related to encryption and 
decryption. When I saw the audio file I am sure that it can be decoded by morse decorder.
I decoded both the file first but still I feel like I am struck inbetween. I took a look on all encryption
software provided in the given hint finally found **Vigenère and Gronsfeld Ciphers** the correct
one and got the correct flag. It took nearly 1 1/2 to solve this challenge.

 
### Flag

The flag which i got is ictf{oahhtweoyymnagutwc}


### 4chan's favorite

### Description

This surely isnt the first time you're seeing this.

### Solution

To solve this question firstly I downloaded Audacity. Then I uploaded the given wav file.
At first I did not know how to solve this question. So i went through some doc about 
audacity and explored some tools inside audacity and found something called as multiview.
By changing to that view I saw a very well know character Rick astley thereby found the 
desired flag.

![image](https://user-images.githubusercontent.com/92567732/176491105-06f1b43e-bdd1-474d-a03f-72c1715f42f5.png)

### Flag

The flag which i got is ictf{rick_astley}


## Reversing

### Baby_rev

### Description

Here is a firmware dump. Can you find the flag?

### Solution
To solve this challenge firstly I downloaded the given bin file. Since I did no had
proper software to open bin file I made use of this [website](https://filext.com/online-file-viewer.html).
As I scrolled through the bin file I found the flag.

![image](https://user-images.githubusercontent.com/92567732/176500572-95c09f48-53d3-4d21-af25-3c82a602bab7.png)

### Flag

The flag which i got is ictf{b30cb82af09abeba892a4242ccfb854977e}


## MISC

### IRC

### Description

Try joining #bi0s_Hardware on Libera Chat

### Solution


To complete this challenge I just opened my browser and searched for **Libera Chat**, clicked
on **CONNECT** in the top right corner and then clicked on **WEBCHAT** and gave the channel name as #bi0s_Hardware 
I found the flag there.

![image](https://user-images.githubusercontent.com/92567732/176510813-74797872-f6a7-44b1-9ae3-e12ad198b3b0.png)
### Flag

I got the flag as 


### Sanity Check - 1

SOLVED

### Sanity Check - 2

SOLVED

## Web

### Inspeccionar_y_disfrutar

### Description


### Solution


I **inspected** the given link first. And then i skimmed through the code and found the blur element.
I clicked on that and i moved to **computed** below. I found the flag in the content section there.

![image](https://user-images.githubusercontent.com/92567732/176512142-ae09ef7e-b23e-4bc3-b534-caa9e869991b.png)

### Flag 

The flag i got is ictf{N4SA_H3k3r}.


## OSINT

### Finding Joey

### Description
During a vacation 2 friends Joey and Chandler went to England to watch Manchester 
United VS Arsenal game, after the game both got drunk and went missing. Chandler 
was searching for Joey all over the place. Luckily Chandler got to call joey and 
told he is in a Bus station behind the building whose photo was taken by Chandler.

### Solution

I used google lens to solve this challenge. First I opened the given image in google 
browser and right clicked on it where I found this option

![image](https://user-images.githubusercontent.com/92567732/176497786-29a9996a-603e-40ac-841a-0eb95a24453e.png)

I got many similar images and results thereby found the flag.

### Flag

The flag which i got is ictf{Canning_Town_Bus_Station}


## Programming

### (net)cat out of the bag

### Description

indy will put desc later.

### Solution

I solved this challenge by **clicking on Start Instance** and copied the provided
command and pasted in the **Ubuntu terminal**. I got the desired flag at the end.

### Flag

The flag which i got is

