# Vuln-Analysis-Model
This project deals with vulnerability analysis and classification using machine learning techniques i.e. Natural Language Processing. 

## Abstract
With the advent of the Internet, systems have become more and more vulnerable over the years. Therefore, it is crucial to assess how vulnerable a system is and what level of protection is required to secure the sensitive data. Hence it gave birth to the process of vulnerability assessment or vulnerability analysis. The whole process has several steps. Mainly, it is required to first identify how vulnerable a system is. Then we need to classify the identified vulnerability in order to assess the impact that the vulnerability can cause to the system, if breached. When it comes to the classification of already identified vulnerabilities, there is a US based database created in the year 2000 which is widely considered as a common reference standard of vulnerability classification. It is known as the National Vulnerability Database (NVD). It uses the Security Content Automation Protocol (SCAP). The security analysts use the common vulnerability scoring system to classify an identified vulnerability. This system is based upon an extensive set of CVSS metrics.


The main idea behind this thesis is to automate the process of assessing these vulnerabilities. In order to avoid the cumbersome and time-consuming process of classifying the gravity of an identified vulnerability, a much swifter and state of the art machine learning based approach to actually predict and foresee the impact of an identified vulnerability is taken. Our research mainly fo- cuses on machine learning based natural language processing (NLP).


The research focuses on two aspects of classifying the impact of an identified vulnerability. Firstly, it focuses on classifying the vulnerability impact in various classes i.e. low, medium, high, critical. Furthermore, based on a regressive model, the system also tries to predict the CVSS score allocated to an identified vulnerability. The results are achieved with considerable precision further discussed in the results section. Deep learning based neural networks are also explored and observed i.e. how using deep learning model impacts the results.


Conclusively, the developed model employs a very robust machine learning based approach to classify and assess identified vulnerabilities. Future works may include further refining the model or use deep learning based models as the National Vulnerability Database grows.
