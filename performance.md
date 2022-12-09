# Performance:

## 1- Usage of CDN(Content Delivery Network):
A content delivery network, or content distribution network, is a geographically distributed network 
of proxy servers and their data centers. The goal is to provide high availability and performance by 
distributing the service spatially relative to end users.

We will try to use CDN in our Flex Management System, because we are actually aiming to make it readily available
for not only Fast-Nuces but also any college or University in the world. So, we have to make data centres accordingly.

![CDN](https://user-images.githubusercontent.com/105812482/206721659-b0e62516-2f6a-4d9e-aa14-4c4ab01e0244.png)

We will somehow try to manage a system as above, to make the data readily available for the particular region.
We aim to have big 7 servers in each of the `Continent` to make data readily available for that particular
Continent. It is all about user convenience and we try to make it easy for users.

## 2- Usage of Cache:
Caching is the process of storing copies of files in a cache, or temporary storage location, so that they can be accessed more quickly. 
Technically, a cache is any temporary storage location for copies of files or data, but the term is often used in reference to 
Internet technologies.

As our Flex management system will be readily available on web also, so that it it is also necessary to use cache and to make 
`latency rate` very minimum.

![web-cache](https://user-images.githubusercontent.com/105812482/206723284-4034f03d-54d9-455c-bdeb-42b60eddaedc.png)

We will actually make a system will this, if our main server is very far away from the user and many requests that 
are similar is coming to us many times, then we will make a server in between them and will do the cache loading in
the server, so that it will only take a long latency rate first time only but not after first time.

Even `Google` also provide the cache loading by the keyword of `cache: website.com`.