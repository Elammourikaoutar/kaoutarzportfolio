---
title: eBanking
publishDate: 2020-03-02 00:00:00
img: /assets/ebanking.png
description: |
  I've develloped a bank account management application.
tags:
  - Angular
  - Java JEE
  - Springboot
  - Hibernate
---

> This project describes the development of a bank account management application, including a DAO layer, services, DTOs, mappers, a web layer (RestControllers), and an Angular frontend interface. The objective is to allow users to create, view, update, and delete bank accounts, as well as perform debit and credit operations.

The first part of the project focuses on setting up the DAO layer, using Spring Boot and JPA. JPA entities such as clients, current accounts, and savings accounts are created, and JPA Repository interfaces are established to interact with the database.

The second part of the project involves the services layer, DTOs, and mappers. Business logic is implemented through services, using DTOs to transfer data between layers, and mappers for object conversion.

The third part focuses on the web layer, exposing REST endpoints via RestControllers. CRUD operations and debit/credit operations are implemented for bank accounts.

The fourth part of the project is dedicated to developing the Angular frontend interface. Angular components and services are created to display account data, allowing users to create, update, and delete accounts, as well as perform debit and credit operations.

Finally, the fifth part of the project deals with security using Spring Security and JWT. Authentication and authorization mechanisms are implemented, using JWT tokens for user authentication.

This video describes how this application works, the tools I've used, and also the source code : https://drive.google.com/file/d/1DAwn0hnKMJgEWpKjNm1n8Lo-ncuxDmgJ/view
