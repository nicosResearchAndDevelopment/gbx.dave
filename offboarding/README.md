# gbx.DAVE Offboarding

GAIAboX DataVerse Maintenance.

## Table of Content

- [Introduction](#introduction)
- [Premises](#premises)
- [Consultation](#consultation)
- [Enter](#enter)
- [Deleting](#deleting)
    - [Example Deleting DataVerse puni](#example-deleting-dataverse-puni)
    - [Deletion Assistance](#deletion-assistance)
    - [Operator Pull Request](#operator-pull-request)
    - [Deleting End](#deleting-end)
- [Deleting by DAVE](#deletion-by-dave)

*Table of Content "GAIAboX DataVerse Offboarding"*.

---

## Introduction

---

## Premises

**DAVE** expects given **Operator** to be authorized to start the process of _DAVE-Offboarding_. So, someone is
acting on behalf ([prov:actedOnBehalfOf](https://www.w3.org/TR/2013/REC-prov-o-20130430/#actedOnBehalfOf)) another
Person and Organization it has to be verified, so DAVE is assured about **Operator** credential.

Given **Operator** is responsible for deletion of given topic.

---

## Consultation

The Candidate (Person, wich aime to become an Operator) need initial instructions.

---

## Enter

1. To become an DAVE **Operator** you have contact TODO:#me.
2. Requesting person gets an Account.
3. Requesting person logs in: TODO:#[https://gbx.nicos-rd.com](https://gbx.nicos-rd.com).

> After successful login given person acts as an **Operator**.

## Deleting

"Deleting", the Process of deleting a topic.

Maintainer branches `gbx.dave-main`.

### Example Deleting DataVerse puni

Path to topic `puni` (shown as a folder '/puni') under folder '/dave' (the folder of all registered DataVerses).

```
gbx.dave
    /dave
        /puni
    /es
```

*Example of deleting the topic 'puni' (The Parallel Universe) which was presented in `gbx.dave` as a DataVerse*.

---

### Deletion Assistance

The Operator need instructions.

### Operator Pull Request

Operator edits data and applies a pull-request to DAVE.

### Deleting End

Pull-Request is accepted by DAVE, Maintaining-branch is merged and will be deleted (and topic/folder is deleted in
gbx.dave-main) .

DAVE will inform **Operator** and related parties.

---

## Deletion by DAVE

The **Operator** instruct **DAVE** to delete the topic.

The topic will be deleted and the Operator and related parties will be informed.

---