## Ex--10-IAM-working-overview

## Aim:
To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.

## Procedure
1. Start the AWS Lab and open the AWS Management Console.

2. Open IAM → Users and verify user-1, user-2, and user-3.

3. Open User groups and verify the groups S3-Support, EC2-Support, and EC2-Admin and their attached policies.

4. Add:

     user-1 → S3-Support

     user-2 → EC2-Support

     user-3 → EC2-Admin

5. Open the IAM Sign-in URL and sign in as each user using the given lab credentials.

6. Test user-1: verify S3 access and confirm EC2 access is denied.

7. Test user-2: verify EC2 read-only access and confirm that stopping an EC2 instance is denied; verify S3 access is denied.

8. Test user-3: open EC2, select LabHost, and stop the instance successfully.

9. Submit the lab and check the Grades/Submission Report.

10. End the lab after completing all tasks.

## Output:

<img width="1919" height="954" alt="Screenshot 2026-08-17 141959" src="https://github.com/user-attachments/assets/8d249260-293d-4ce8-a198-13b0011b4cdc" />
<img width="1919" height="1028" alt="Screenshot 2026-08-17 142430" src="https://github.com/user-attachments/assets/259ac3ae-d9b3-4c35-ad9e-e9cae525f8c4" />
<img width="1919" height="1029" alt="Screenshot 2026-08-17 142647" src="https://github.com/user-attachments/assets/94aa6efd-a430-4944-a1e1-d1cf9972421b" />
<img width="1919" height="1027" alt="Screenshot 2026-08-17 142911" src="https://github.com/user-attachments/assets/34d0415f-2d3a-4eb2-a966-1f0cd41d5a33" />
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/a55f8910-174b-4fc9-9f91-db6cb9784dae" />
<img width="1919" height="1028" alt="Screenshot 2026-08-17 142430" src="https://github.com/user-attachments/assets/458ec054-0582-4ea1-b570-0c85d058982f" />

## Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. user-1 received S3 read-only access, user-2 received EC2 read-only access, and user-3 received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
