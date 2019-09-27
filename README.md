# Apiman Gateway Docker image
The manager component of the [Apiman](http://www.apiman.io/) - Open Source API Management project. 
This image was build as described in the [official documentation](http://www.apiman.io/latest/production-guide.html).

### Available tags
 - on wildfly11: ```1.5.1```, ```latest```

## What is [Apiman](http://www.apiman.io/)?
From Apiman website:
> The apiman project brings an open source development methodology to API Management, 
> coupling a rich API design & configuration layer with a blazingly fast runtime.
> Features:
>  - **Govern Your APIs** - Flexible, policy-based runtime governance for your APIs. Offer the same API through multiple plans, allowing different levels of service to different API consumers.
>  - **Rich Management Layer** - Use the rich management layer (REST API and separate UI) to manage/configure not only APIs but also the client applications that consume them.
>  - **Easily Embeddable** - Embed the API Management Policy Engine in any application - it has a small footprint and can be completely independent from the management layer.
>  - **Fully Asynchronous** - The runtime engine's API is fully asynchronous and is designed to run equally well in both a standard Java EE environment and newer async runtimes like Vert.x.

The Apiman project is composed of two main components. A **gateway** and 
a **manager** and their dependencies.