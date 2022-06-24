<div id="top"></div>


<br />
<div align="center">
  
  <h3 align="center">TigerGraph-Deployment-with-Ansible</h3>

  <p align="center">
    Deploy TigerGraph using Ansible
    <br />
    <a href="https://www.tigergraph.com/"><strong>Explore TigerGraph »</strong></a>
    <br />
    <br />
    <a href="https://docs.tigergraph.com/tigergraph-server/current/installation/install">TigerGraph Direct Install Documentation</a>
    ·
    <a href="https://github.com/Saurabh-Thakre/TigerGraph-Deployment-with-Ansible/issues">Report Bug</a>
    ·
    <a href="https://github.com/Saurabh-Thakre/TigerGraph-Deployment-with-Ansible/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Normally, TigerGraph can be installed directly from the steps mentioned in TigerGraph's Installtion documentation which includes installtion using shell script. In this Project, I have tried to give it a future thinking to install TigerGraph using Ansible.

Here's why:
* Modular
* Idempotency
* Simple and readable. No special coding skills needed.
* You can orchestrate complete application lifecycle using Ansible :smile:

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

Following are the tech stack used to create this project.

* [Ansible](https://www.ansible.com/)
* [Shell](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

You don't have much to do to install TigerGraph with Ansible. Just make sure you're going through below steps. Have fun ;)

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Ansible
  [Installing Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
  After installing, check Ansible version with following command
  ```sh
  ansible --version
  ```

### Installation

1. Download the tar file from following google drive [link](https://drive.google.com/file/d/1aMDNV1ujpYMI663ddodsnwjMCSwzznLe/view?usp=sharing)
2. Untar the download tar.gz file
   ```sh
   tar -zxvf tigergraph-3.5.3-offline-ansible-deployment.tar.gz
   ```
3. Go to the Ansible deployment directory
   ```sh
   cd tigergraph-3.5.3-offline-ansible-deployment/ansible_deployment
   ```
4. Fill the path variable in inventory file 
   ```sh
   vi inventory
   path='<path-to-tigergraph-3.5.3-offline-ansible-deployment-directory>'
   ```
5. Run ansible playbook
   ```sh
   ansible-playbook -i inventory install.yml -vvvv
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add gsql examples to show how amazing tgraph is. 

See the [open issues](https://github.com/Saurabh-Thakre/TigerGraph-Deployment-with-Ansible/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Saurabh Thakre - [@saurabh_thakre_](https://twitter.com/saurabh_thakre_)

Project Link: [TigerGraph-Deployment-with-Ansible](https://github.com/Saurabh-Thakre/TigerGraph-Deployment-with-Ansible/)

<p align="right">(<a href="#top">back to top</a>)</p>
