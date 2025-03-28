# FedRAMP Websitep [https://www.fedramp.gov/](https://www.fedramp.gov/)

Welcome! This repository contains the source code for the **FedRAMP website**. The documentation provided in this README is meant to help your get an base understanding of the code that runs this website, along with how to get a local version up and running on your machine.

---

## Running the Website Locally  

This site is built using:  
- [Jekyll](https://jekyllrb.com/), a static site generator

Follow the steps below to set up the site on your local machine.  

### Prerequisites  

Before getting started, make sure you have the following installed:  

1. **Git** – [Installation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)  
1. **Ruby** – Version specified in [.ruby-version](https://github.com/uswds/uswds-site/blob/main/.ruby-version) or [.tool-versions](https://github.com/uswds/uswds-site/blob/main/.tool-versions)  
   - [Installation guide](https://www.ruby-lang.org/en/documentation/installation/)      

---

## Installation  

1. **Clone the repository:**  
   ```sh
   git clone https://github.com/GSA/fedramp-gov.git
   ```  

2. **Navigate into the project folder:**  
   ```sh
   cd fedramp-gov
   ```  

3. **Install dependencies:**  
   ```sh
   bundle install
   ```  

4. **Start the local server:**  
   ```sh
   bundle exec jekyll serve
   ```  

5. **View the site in your browser:**  
   Open [http://127.0.0.1:4000](http://127.0.0.1:4000) to see the site running locally.  


## Deployment & Previews  

The site is deployed using [cloud.gov Pages](https://cloud.gov/pages/).  
- Changes pushed to the `main` branch will automatically update the live site.  
- Public previews are generated for each branch pushed to GitHub.    

---

## Contributing  

We welcome contributions! Please review our [contributing guidelines](CONTRIBUTING.md) before opening an issue or submitting a pull request. These guidelines cover our coding standards and best practices.  

---

### 🎉 Thanks for Supporting FedRAMP!  

We appreciate your contributions to making digital services better and more accessible for everyone. 🚀 