# Microservice with Node JS and React

<br/>

## Readme Coming Soon...

<!-- ## How to run project in development mode (current version)

<br/>

```
$ kubectl create secret generic jwt-secret --from-literal=JWT_KEY=MY_JWT_SECRET
```

<br/>

**stripe.com**

Developers --> API keys

<br/>

```
// <STRIPE_SECRET_KEY> from stripe.com
$ kubectl create secret generic stripe-secret --from-literal=STRIPE_KEY=<STRIPE_SECRET_KEY>
```

<br/>

### Requests to app

```
// SIGN UP
$ curl \
    --insecure \
    --cookie-jar /tmp/cookies.txt \
    --data '{"email":"marley@example.com", "password":"123456789"}' \
    --header "Content-Type: application/json" \
    --request POST \
    --url https://ticketing.dev/api/users/signup \
    | jq
```

<br/>

```
// SIGN IN
$ curl \
    --data '{"email":"marley@example.com", "password":"123456789"}' \
    --header "Content-Type: application/json" \
    --request POST \
    --url http://ticketing.dev/api/users/signin \
    | jq
```

<br/>

```
// GET CURRENT USER
$ curl \
    --insecure \
    --cookie /tmp/cookies.txt \
    --header "Content-Type: application/json" \
    --request GET \
    --url https://ticketing.dev/api/users/currentuser \
    | jq
```

<br/>

```
// CREATE TICKET
$ curl \
    --insecure \
    --cookie /tmp/cookies.txt \
    --data '{"title":"concert", "price":10}' \
    --header "Content-Type: application/json" \
    --request POST \
    --url https://ticketing.dev/api/tickets \
    | jq
```

<br/>

```
// GET ALL TICKETS
$ curl \
    --insecure \
    --header "Content-Type: application/json" \
    --request GET \
    --url https://ticketing.dev/api/tickets/ \
    | jq
```

<br/>

```
// GET TICKET
$ curl \
    --insecure \
    --header "Content-Type: application/json" \
    --request GET \
    --url https://ticketing.dev/api/tickets/6037eaacbcc4a0001acb6d50 \
    | jq
```

<br/>

```
// UPDATE TICKET
$ curl \
    --insecure \
    --cookie /tmp/cookies.txt \
    --data '{"title":"new concert", "price":100}' \
    --header "Content-Type: application/json" \
    --request PUT \
    --url https://ticketing.dev/api/tickets/603b0e8036b9f80019154277 \
    | jq
```

<br/>

```
// CREATE ORDER
$ curl \
    --insecure \
    --cookie /tmp/cookies.txt \
    --data '{"ticketId":"604150ce9a43b7001a54b720"}' \
    --header "Content-Type: application/json" \
    --request POST \
    --url https://ticketing.dev/api/orders \
    | jq
```

<br/>

```
// GET ALL ORDERS
$ curl \
    --insecure \
    --cookie /tmp/cookies.txt \
    --header "Content-Type: application/json" \
    --request GET \
    --url https://ticketing.dev/api/orders \
    | jq
```

<br/>

```
// GET SINGLE ORDER
$ curl \
    --insecure \
    --cookie /tmp/cookies.txt \
    --header "Content-Type: application/json" \
    --request GET \
    --url https://ticketing.dev/api/orders/604150e7d42b880019802e99 \
    | jq
```

<br/>

```
// CREATE PAYMENT
$ curl \
    --insecure \
    --cookie /tmp/cookies.txt \
    --data '{"orderId":"5ec6c93f6c627e0023725faf", "token": "tok_visa"}' \
    --header "Content-Type: application/json" \
    --request POST \
    --url https://ticketing.dev/api/payments/ \
    | jq
```

<br/>

---
 -->
