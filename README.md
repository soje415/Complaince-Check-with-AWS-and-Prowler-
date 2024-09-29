## Complaince-Check-with-AWS-and-Prowler-


Automating complaince check with AWS and Prowler, with detailed recommendations for remediation.

##Project Overview


This project showcases how I utilized Prowler, an open-source security tool, to run an automated compliance check against the CIS AWS Foundations Benchmark (v3.0). This ensures that my AWS environment aligns with the security best practices defined by CIS (Center for Internet Security). Below, I walk through the process, tools used, and results, with step-by-step instructions and screenshots for reference.

##Tools Used


  Prowler: Security tool to check compliance in AWS.
  AWS CloudShell: An online shell environment to interact with AWS.
  Python >= 3.9: Required to install Prowler.
  CIS AWS Foundations Benchmark v3.0: The benchmark standard I audited   against.

![1](https://github.com/user-attachments/assets/734f07dc-632b-4101-9726-07cdd74b7fe9)


![2](https://github.com/user-attachments/assets/57360cbb-bcf0-479d-8f80-348b75c7346b)


![3](https://github.com/user-attachments/assets/7105ca8e-1a6b-430a-9880-c223983bd3cc)

![4](https://github.com/user-attachments/assets/cfa8fc90-0b1c-4473-8691-2d6b8d7bfe24)


![5](https://github.com/user-attachments/assets/0be114fd-f52b-4d79-b821-fd0630c0578a)

![6](https://github.com/user-attachments/assets/7e983cbf-8e1f-49f4-aa77-a9d769628daf)


![7](https://github.com/user-attachments/assets/8a5a9ac7-7a3c-45a5-99bc-11750a8164eb)


![8](https://github.com/user-attachments/assets/cceb13a2-8384-4e59-84a6-c2accfa9f76e)

![9](https://github.com/user-attachments/assets/1e046735-739e-4640-9e87-8a3de0acf080)

![10](https://github.com/user-attachments/assets/a755a8d0-f8a4-4d65-aa78-67e9ce74b2bf)


![11](https://github.com/user-attachments/assets/f4b30b5d-16db-4e8e-b092-2ebda16598a4)


![finding](https://github.com/user-attachments/assets/b1e6a6b8-c2ca-4dde-9e7b-830e8e75724c)



##Conclusion


Running Prowler in AWS CloudShell is an efficient way to automate compliance checks against the CIS AWS Foundations Benchmark. By following this process, I ensured that my AWS environment adheres to the latest security standards. The ability to run these checks regularly and view detailed reports makes Prowler a valuable tool for AWS security.


##Future Work
I plan to automate this process further by integrating Prowler checks into a CI/CD pipeline, running compliance checks automatically whenever infrastructure changes occur.
