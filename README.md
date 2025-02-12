LENDit

LENDit is a web application where users can lend and borrow items from other users for a specific period of time.


built using Ruby on Rails, HTML, SCSS, and JavaScript. It provides a platform for managing and displaying content with seamless media integration through Cloudinary.

Features

Search the web for interesting products
Upload your products to earn some money
Make a reservation for a product
Chat with the product owner about details
Check a user reviews
Check a product review
Star products
Filter by category
Search in the navbar
See the location of the product on the map
Check your 'Pending' 'Accepted' 'Ongoing' or 'Finished' lends & Borrows


To get started with the project, follow these steps:

1. Clone the Repository
First, clone the repository to your local machine:

git clone https://github.com/borrellBR/LENDit.git

2. Install Dependencies
Install the required gems and packages using Bundler:

bundle install

3. Configure Environment Variables
Create a .env file in the root directory of the project and add the following environment variables:

(This is necessary to be able to see the product images, and get a better understanding, but not mandatory to run the web app)

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

For any help during the .env process, please contact me on: ignacioborrellr@gmail.com

4. Run the Application
Finally, start the Rails server:

rails s
Now you can access the application at http://localhost:3000.
