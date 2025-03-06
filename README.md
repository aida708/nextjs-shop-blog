**Next.js Challenge - Shop & Blog**

This project is a Next.js-based eCommerce and blog platform utilizing json-server as a mock backend. It includes product listings, blog posts, filtering, search functionality, and pre-rendering techniques like getStaticProps and getServerSideProps.

**Features**

Home Page: Banner, category picker, featured products, and blogs.

About Page: Static page with fetched content.

Shop Overview: Product listing with filtering (gender, search).

Product Detail: Displays detailed product information with related products.

Blog Overview: Blog listing with category-based filtering.

Blog Detail: Displays full blog content with related blogs.

Search Page: Searches across both products and blogs.

**Tech Stack**

Next.js

React

Material UI (if applicable)

json-server

Axios

CSS Modules / Styled Components (depending on usage)

**Installation**

Clone the repository:

git clone https://github.com/yourusername/nextjs-shop-blog.git
cd nextjs-shop-blog

**Install dependencies:**

npm install

**Run the JSON Server:**

npm run server

**Start the Next.js development server:**

npm run dev

**API Endpoints**

The mock API runs on http://localhost:5001 with the following endpoints:

Banner Content: /banner_content

About Page: /about_page

Products: /products

Blogs: /blogs
