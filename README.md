# LENDit

LENDit is a web application where users can lend and borrow items from other users for a specific period of time. It is built using Ruby on Rails, HTML, SCSS, and JavaScript, providing a platform for managing and displaying content with seamless media integration through Cloudinary.

---

## Features

- **Search the Web for Interesting Products**: Easily find the products you're looking for.
- **Upload Your Products to Earn Some Money**: List your own products to lend and make money.
- **Make a Reservation for a Product**: Reserve products from other users.
- **Chat with the Product Owner About Details**: Communicate directly with product owners.
- **Check User Reviews**: View feedback from other users.
- **Check Product Reviews**: See ratings and reviews for each product.
- **Star Products**: Favorite your preferred products.
- **Filter by Category**: Filter items based on categories.
- **Search in the Navbar**: Quickly search for products via the search bar in the navbar.
- **See the Location of the Product on the Map**: View the geographical location of products.
- **Check Your Lend & Borrow Status**: Manage your products under 'Pending', 'Accepted', 'Ongoing', or 'Finished' categories.

---

## Getting Started

To get started with the project, follow these steps:

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/borrellBR/LENDit.git
```

### 2. Install Dependencies

Install the required gems and packages using Bundler:

```bash
bundle install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory of the project and add the following environment variables:

**(This is necessary to be able to see the product images and get a better understanding, but not mandatory to run the web app)**

```bash
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

For any help during the `.env` process, please contact me at:  
**ignacioborrellr@gmail.com**

### 4. Run the Application

Finally, start the Rails server:

```bash
rails s
```

Now you can access the application at [http://localhost:3000](http://localhost:3000).

---

## Contributing

Feel free to fork this project, make improvements, and create pull requests. Contributions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Let me know if you'd like any further changes!
