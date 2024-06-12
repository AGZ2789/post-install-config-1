<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

![](https://i.imgur.com/waxVImv.png)

<h1>osTicket - Post-Install Configuration</h1>

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />
- [<b>Simple List</b>](https://docs.google.com/document/d/1JfsM1LRBu6UfCGy1wkADmG3cRzhmuzEoTLt9BRisgQ4/edit?usp=sharing)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure:
  - Roles
  - Departments
  - Teams
  - Agents (Workers)
  - Users (Customers)
  - SLA (Service Level Agreements)
  - Help Topics

<h2>Configuration Steps</h2>


- <h2>Configure Roles</h2>

  - Navigate to Admin Panel -> Agents -> Roles.
  - Create the "Supreme Admin" role.

![Snipaste_2024-05-15_19-56-43](https://github.com/AGZ2789/post-install-config-1/assets/84995125/f08771c3-f691-4107-b5ca-8eef5f56e2f6)

![Snipaste_2024-05-15_19-58-42](https://github.com/AGZ2789/post-install-config-1/assets/84995125/9c457571-4bbd-4405-b17d-794d66a34138)

![Snipaste_2024-05-16_18-17-54](https://github.com/AGZ2789/post-install-config-1/assets/84995125/53595bfe-ca1a-4897-b250-bb486de719b5)

![Snipaste_2024-05-16_18-31-38](https://github.com/AGZ2789/post-install-config-1/assets/84995125/296df7e1-265f-437f-9086-d3c5547d98ab)

![Snipaste_2024-05-16_18-37-18](https://github.com/AGZ2789/post-install-config-1/assets/84995125/26cb76d1-db78-4c3b-a1f6-9cb825daace4)

![Snipaste_2024-05-16_18-52-18](https://github.com/AGZ2789/post-install-config-1/assets/84995125/9250cc6d-26f9-4db1-823a-d0426552f4e3)

![Snipaste_2024-05-16_19-08-54](https://github.com/AGZ2789/post-install-config-1/assets/84995125/c129aa94-6908-4ede-8fb0-cd9ef6062707)



- <h2>Configure Departments</h2>

  - Admin Panel -> Agents -> Departments.
  - Create the "System Administrators" department.

![Snipaste_2024-05-16_19-08-54](https://github.com/AGZ2789/post-install-config-1/assets/84995125/18a5e2b6-f6cd-4820-a98f-59cd3d4fc10e)

![Snipaste_2024-05-16_19-13-10](https://github.com/AGZ2789/post-install-config-1/assets/84995125/74aea40b-be3a-499e-9b02-d10e63e9d78d)

![Snipaste_2024-05-16_19-34-40](https://github.com/AGZ2789/post-install-config-1/assets/84995125/32167331-fca3-4aac-8adf-123db72ee738)



- <h2>Configure Teams</h2>

  - Admin Panel -> Agents -> Teams.
    - Create "Level I Support" team.
    - Create "Level II Support" team.

![Snipaste_2024-05-16_19-34-40](https://github.com/AGZ2789/post-install-config-1/assets/84995125/eff35cdf-2816-4375-9832-530a936f5de9)

![Snipaste_2024-05-16_19-40-13](https://github.com/AGZ2789/post-install-config-1/assets/84995125/3460e29b-8c09-4dc4-98fe-92084872e5e6)



- <h2>Allow anyone to create tickets</h2>

  - Admin Panel -> Settings -> User Settings.
  - Enable "Registration Required" to require registration and login to create tickets.

![Snipaste_2024-05-16_19-46-45](https://github.com/AGZ2789/post-install-config-1/assets/84995125/1a085887-3c1e-4820-baab-f2af0315f9aa)


- <h2>Configure Agents (workers)</h2>

  - Admin Panel -> Agents -> Add New.
    - Add agents "Jane" and "John".

![Snipaste_2024-05-16_19-50-51](https://github.com/AGZ2789/post-install-config-1/assets/84995125/dda4d208-1088-4870-a0fe-45ccaa89a422)

![Snipaste_2024-05-16_19-56-25](https://github.com/AGZ2789/post-install-config-1/assets/84995125/bfbe5d7e-8008-4014-b9f2-4272e90236c0)

![Snipaste_2024-05-16_19-59-20](https://github.com/AGZ2789/post-install-config-1/assets/84995125/dbf15a4e-2042-42c2-8748-8128e01b4230)

![Snipaste_2024-05-16_20-08-39](https://github.com/AGZ2789/post-install-config-1/assets/84995125/528c7bdb-8423-4134-8355-d24d64dc73bf)

![Snipaste_2024-05-17_21-21-25](https://github.com/AGZ2789/post-install-config-1/assets/84995125/fbd11c26-0220-490a-8043-3276d41a8b65)


- <h2>Configure Users (customers)</h2>

  - Agent Panel -> Users -> Add New.
    - Add users "Karen" and "Ken".

![Snipaste_2024-05-17_21-23-13](https://github.com/AGZ2789/post-install-config-1/assets/84995125/6463a49d-fc54-461f-a903-04f531cdac0f)

![Snipaste_2024-05-17_21-25-15](https://github.com/AGZ2789/post-install-config-1/assets/84995125/99039259-3709-4747-b5ee-db307dcb23ac)


- <h2>Configure SLA</h2>

  - Admin Panel -> Manage -> SLA.
    - Define SLA levels:
    - Sev-A (1 hour, 24/7)
    - Sev-B (4 hours, 24/7)
    - Sev-C (8 hours, business hours)

![Snipaste_2024-05-17_21-30-21](https://github.com/AGZ2789/post-install-config-1/assets/84995125/cb49498a-f59b-449d-bae9-8df5af99791a)

![Snipaste_2024-05-17_21-32-51](https://github.com/AGZ2789/post-install-config-1/assets/84995125/013638d3-c1ac-43ec-a43e-bfb4cc754ee8)

![Snipaste_2024-05-17_21-34-11](https://github.com/AGZ2789/post-install-config-1/assets/84995125/8c0b18d8-f994-47a7-8e7b-79a225fdf553)

![Snipaste_2024-05-17_21-37-12](https://github.com/AGZ2789/post-install-config-1/assets/84995125/a3f7215b-4f6f-4855-ac4a-845be559c011)

![Snipaste_2024-05-17_21-41-03](https://github.com/AGZ2789/post-install-config-1/assets/84995125/853383c1-ffb5-4acb-9d60-9a04a44ccc92)

![Snipaste_2024-05-17_21-42-26](https://github.com/AGZ2789/post-install-config-1/assets/84995125/7b7d8eb1-550e-4e11-9ec3-ed90ca6eb09a)


- <h2>Configure Help Topics</h2>

  - Admin Panel -> Manage -> Help Topics.
    - Create help topics:
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset

![Snipaste_2024-05-17_21-47-00](https://github.com/AGZ2789/post-install-config-1/assets/84995125/41dc3602-d51e-4a44-8c78-c1216ed80c39)

![Snipaste_2024-05-17_21-49-44](https://github.com/AGZ2789/post-install-config-1/assets/84995125/d8d6c2b5-d184-4a03-8f31-077f8eccf2e4)

![Snipaste_2024-05-17_21-51-27](https://github.com/AGZ2789/post-install-config-1/assets/84995125/b88be8d2-4f2d-41d7-8b74-d96d3f3c7fab)

![Snipaste_2024-05-17_21-56-07](https://github.com/AGZ2789/post-install-config-1/assets/84995125/7b804252-a316-4c1a-9850-8479eb1342d2)

