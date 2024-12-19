# Sprint-Boot-for-Java  

## **Step 1:**  
Open your web browser within the lab environment and go to [Spring Initializr](https://start.spring.io/)  

---

## **Step 2:** Configure the following options:  

- **Project:** Select **Maven**.  
- **Language:** Select **Java**.  
- **Spring Boot Version:** Choose **3.3.5** (or the latest stable version).  

**Important:**  
Avoid using **SNAPSHOT** versions, as they are under development and unstable.

---

## **Step 3:** Enter the project metadata as follows:  

- **Group:** `com.quickcart`  
  _(The organization or company that owns the project. Here, it represents the QuickCart organization.)_  

- **Artifact:** `ecommerce`  
  _(The project or module name representing the e-commerce application for QuickCart.)_  

- **Name:** `QuickCart`  
  _(The application's display name, used for documentation and project management.)_  

- **Description:** `An e-commerce application for managing and displaying products in an online store`  
  _(A brief project description; optional.)_  

- **Package Name:** `com.quickcart.ecommerce`  
  _(The root package for Java code, ensuring organization and a standard naming convention.)_  

- **Packaging:** Choose **JAR** or **WAR**:  
  - **JAR:** For standalone apps with embedded Tomcat (recommended).  
  - **WAR:** For deploying apps to external servers.  

- **Java Version:** Choose a compatible version like **Java 17**, **Java 21**, or **Java 23**.  
  _(Java 21 is the latest Long-Term Support version and a good choice for new projects.)_

---

## **Step 4:** Click the **Add Dependencies** button on the right-hand side of the page.  

- **Add Spring Web:**  
  - Select **Spring Web** from the **Web** section (for building web applications).  
  - Press **Enter** or click on it to add it to the project.  

**Remember:**  
Dependencies are external libraries your project relies on. They provide ready-made code for common tasks. For example, **Spring Web** simplifies building web apps using Spring MVC and includes Tomcat for running your app locally.

---

## **Step 5:**  
Click the **Generate** button to download a compressed file named `ecommerce.zip`.  

---

## **Step 6:**  
Unzip the downloaded project:  
- Double-click the `.zip` file.  
- Click the **Extract** button.  

In your lab environment, open **IntelliJ** by double-clicking its icon.

---

## **Step 7:**  
Open the unzipped project in **IntelliJ** and ensure that all dependencies are loaded.
