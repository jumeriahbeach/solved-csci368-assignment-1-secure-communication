Download Link: https://assignmentchef.com/product/solved-csci368-assignment-1-secure-communication
<br>
<p class="message-text">Aims

<p class="message-text">This assignment aims to establish a basic familiarity with the cryptographic methods and provides an exercise of key establishment and secure communication in a networked environment.

<p class="message-text">Objectives On completion of this assignment you should be able to:

<p class="message-text"> Understand some basic concepts in cryptography.

<p class="message-text"> Understand key exchange and secure communication.

<p class="message-text"> Understand network programming.

<p class="message-text">Specifications:

<p class="message-text">Write (Java or C/C++) TCP programs allowing two parties to establish a secure communication channel. For simplicity, let us call programs “Host” and “Client”; each can be used by a user. Again, for simplicity, let us assume that Alice uses Host and Bob uses Client. Alice and Bob want to establish a secure communication channel where messages are encrypted with AES. They need to carry out the following tasks.

<p class="message-text">(1) Establish a share AES session key so that they can use it to encrypt messages.

<p class="message-text">(2) Use the shared key to secure the communication. The key establishment is done by the Diffie-Hellman Exchange scheme. Assume that Alice has a pair of private/public keys (x1, y1) and Bob has a pair of private/public keys (x2,