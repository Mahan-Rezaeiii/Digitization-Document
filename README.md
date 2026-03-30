# **Digitization Document II via Tabula-Py (Winter 2025)**

This repository contains a sample of my work as a Research Assistant to **[Dr. Sepehr Ekbatani](https://sepehrekbatani.com/)** and **[Dr. Sahber Ahmadi-Renani](https://sites.google.com/view/ahmadirenani/home)** at the Department of Economics at the [Tehran Institute for Advanced Studies (TeIAS)](https://teias.institute/).

---

## **Overview**

This project contains the data section of the working paper *"Geography of Higher Education Opportunity and the Role of Place-Based Policies,"* by **[S. Ahmadi-Renani](https://sites.google.com/view/ahmadirenani/home)** and **[S. Ekbatani](https://sepehrekbatani.com/)**. (Draft not available)

As a research assistant, I digitized PDFs published by Iran’s National Organization of Educational Testing (`NOET`) that report detailed seat allocations for the national university entrance exam (`Konkour`) across all universities for the period 2012–2020. 

[Official Data Source Link](https://asnad.sanjesh.org/)

 This is the first time this data has been digitized. The data provides insights into the <span style="color:red">supply side</span> of Iran's higher education system and is classified at the university level.

This data includes the following features:

- Number of seats by gender, field of study, and major
- Type of admission or acceptance category
- Major codes used in the national entrance exam system
- ...

---

## **From PDF to Dataset**

In this project, I used the *"Tabula-Py"* library for the digitization process. This library is specifically designed to extract tables from PDFs, making it suitable for **`Machine-Readable`** documents. It relies on **`Coordinates`** within the PDF to perform the digitization. This library works best with structured, table-rich documents.

In my code folder, I provided explanations for each step I took to digitize a sample document and convert it into a well-structured DataFrame in CSV format.

---

## **Contact**
If you have any questions or feedback, feel free to reach out via email: mahanrezaee98@gmail.com.
