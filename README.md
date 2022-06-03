# zk-Crush

zk-Crush is a way to tell your crush you like them with [zero-knowledge](https://en.wikipedia.org/wiki/Zero_knowledge#:~:text=Zero%20knowledge%20may%20mean%3A,the%20veracity%20of%20the%20statement).

<img width="1511" alt="overview" src="https://user-images.githubusercontent.com/7995105/171797030-0985d474-2aeb-44dd-935e-ff5e1ce1ad1b.png">

### How it works

The idea is that we hash the name of your crush, then people can hash their name and check if their hash matches the hash of the crush you've provided. Therefore it's zero-knowledge because we don't store your name, we only know the hash, so finding a hash that matches corresponds to knowing the pre-image to the hash. Also note that this is entirely client-side, we store nothing on a server.

### How to use it

Very simple, you enter your name and the name of a crush, then click generate.

It will generate a URL that you will be able to publicly share.

<img width="1510" alt="example" src="https://user-images.githubusercontent.com/7995105/171797054-2fd84ba8-00ae-4bc4-8eb2-204491f40e0b.png">

When people go to this URL, they can enter their name, to generate the hash of their name and see if it matches the hash of your crush. If it doesn't, no harm done, if it does, they now know!


<img width="1507" alt="notmatch" src="https://user-images.githubusercontent.com/7995105/171797129-f7079d7c-3392-4243-8202-ea1be508e546.png">
<img width="1512" alt="match" src="https://user-images.githubusercontent.com/7995105/171797130-7add2029-8217-44ce-bcaf-f3dec21cd7d2.png">

Note this is mostly a joke and a toy, do not use this if you stand to seriously lose something!
