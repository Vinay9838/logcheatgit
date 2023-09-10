# Log Cheat

---

---
### Table of Contents

| No. | Usage |
| --- | --------- |
|1  | [Get first 10 lines of log.](#get-first-10-lines-of-log) |
|2  | [Get first n lines of log.](#get-first-n-lines-of-log) |
|3  | [Get first n bytes of log.](#get-first-n-bytes-of-log) |
|4  | [Get last 10 lines of log.](#get-last-10-lines-of-log) |
|5  | [Get last n lines of log.](#get-last-n-lines-of-log) |
|6  | [Get last n bytes of log.](#get-last-n-bytes-of-log) |
|7  | [Get latest and wait for addition log.](#get-latest-and-wait-for-addition-log) |
|8  | [Use of less.](#use-of-less) |



## Core Concepts


1. ### Get first 10 lines of log.
```shell
 head info.log
```   
   **[⬆ Back to Top](#table-of-contents)**

2. ### Get first n lines of log.
```shell
 head -n 50 info.log
```   
   **[⬆ Back to Top](#table-of-contents)**

3. ### Get first n bytes of log.
```shell
 head -c 50 info.log
```   
   **[⬆ Back to Top](#table-of-contents)**

4. ### Get last 10 lines of log.
```shell
 tail info.log
```   
   **[⬆ Back to Top](#table-of-contents)**

5. ### Get first n lines of log.
```shell
 tail -n 50 info.log
```   
   **[⬆ Back to Top](#table-of-contents)**

6. ### Get first n bytes of log.
```shell
 tail -c 50 info.log
```   
   **[⬆ Back to Top](#table-of-contents)**

7. ### Get latest and wait for addition log.
```shell
 tail -f info.log
```   
   **[⬆ Back to Top](#table-of-contents)**

8. ### Use of less.
```shell
 less info.log
 /: Search
 n: Next
 G: Start of the file
 spance: Display next page
```

   **[⬆ Back to Top](#table-of-contents)**

