<h1>Immutable Infrastructure Using Packer</h1>

<h3><i> Learn more about from my article </i></h3> please visit <a href="https://faun.pub/what-why-how-is-packer-a7a362e95f51">here</a>.

We get started by using terraform to provision our servers and later employing ansible on instances for configuration management. This allows us to add times when provisioning servers. So that the process will not continue until configuration completes. In terms of configuration, we will be using Packer. Packer is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

<h2>Command to run Packer</h2>

Provide subnet id created in network terraform in packer.json

packer build packer.json


