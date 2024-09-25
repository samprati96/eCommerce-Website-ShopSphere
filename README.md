# ShopSphere

ShopSphere is an E-Commerce web application built with Ruby on Rails. This repository contains the source code for an interactive online shopping platform that allows users to browse products, manage their accounts, and place orders. Designed with a user-friendly interface and responsive layout, ShopSphere aims to provide a seamless shopping experience.


## Features

### Application
- User authentication using the BCrypt gem
- ADMIN and User roles
- Product icons stored on Google Cloud or Amazon Cloud
- Email account activation
- Users can follow one another
- Twitter-like feed mechanism for followers
- Attractive search bars
- Elegant pagination
- Users can post articles
- Add products to cart
- Place orders
- Admin functionality to edit or delete orders

### In Progress
- Implementing a state machine
- Utilizing more Ajax requests
- Ticket system implementation
- Shipping integration

Images from Version 1.0

| Home  | Users |
|:---:|:---:|
| ![home](https://github.com/user-attachments/assets/55ff2845-66b8-40d2-b231-2819d3857aa7) | ![users](https://github.com/user-attachments/assets/50992660-6fcc-405a-8968-c91c8d157323) |

| Orders  | Articles |
|:---:|:---:|
| ![orders](https://github.com/user-attachments/assets/19fe97aa-4ce0-4386-8e74-a7305b8aae82) | ![articles](https://github.com/user-attachments/assets/88c6505e-a6c1-40a4-8a64-f13295aef4e9) |

Cart:
![cart](https://github.com/user-attachments/assets/412ccfc3-673f-401b-806c-c5a156ce1018)


---

## Getting Started

To set up the app, clone the repository and install the necessary gems:

```bash
$ bundle install --without production
```

Next, migrate the database:

```bash
$ rails db:migrate
```

Finally, run the test suite to verify everything is functioning correctly. Note: some tests may fail as they haven't been fully corrected yet!

```bash
$ rails test
```

If the test suite passes, you'll be ready to run the app on a local server:

```bash
$ rails server
```
