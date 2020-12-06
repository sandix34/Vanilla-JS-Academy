If there’s data in localStorage, and it hasn’t expired, use it.
Otherwise, call the API to get fresh data.
If the API fails and there’s expired data in localStorage, use that instead.

---

![apicachefallback](https://user-images.githubusercontent.com/44428775/101280818-8d184980-37cb-11eb-979a-c21def472453.png)