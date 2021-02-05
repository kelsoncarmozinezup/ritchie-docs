---
title: Glossary
weight: 103
description: You will find in this section more about common concepts on development field.
---

---

## CLI

It refers to a command line interface, which is a program that processes commands in a software or any computing program only through text. 

## Credential

It refers to reusable input parameters that you can use in Ritchie \(example: access data for any tool or api\).

## Environment

On Ritchie, each environment will have its own credentials, which can be necessary to execute specific formulas through the CLI.   
  
_For example: it's possible to create a **professional** and a **personal** environments \(or **prod** and **staging**\) with different credentials, and switch from an environment to another according to the necessity._

## Formula

On Ritchie's context, a formula is a script that can be executed through a command line once it has been adapted to Ritchie structure. It allows the user to execute it locally or through Docker and with its necessary dependencies.

## JSON

It refers to JavaScript Object Notation \(JSON\), that is a standard text based **format** used to structure data created with Java programming language.

## Tree

It refers to a group of commands organized on Ritchie. You can click on the next link to understand more about [**Tree's structure**](key-concepts#command-tree).

## Repository

A storage place you can organize features, commands or any files and/or files necessary to use a tool. On Ritchie, there are three repositories created to manage formulas, the server and contributions we receive.

* [**ritchie-cli**](https://github.com/ZupIT/ritchie-cli)
* [**ritchie-formulas**](https://github.com/ZupIT/ritchie-formulas)

## Standard Streams

It refers to a communication channel that allows input and output interconnection between a computer program and its environment.

On Ritchie, we use the standard input \(stdin\) to execute commands automatically.