I prepared this documenttaion page for myself, adding the steps I used in this project.
##Content Management with Strapi

### Step 1: Installing Strapi

Strapi is a headless CMS (Content Management System) designed for backend management of content. It allows you to centrally manage content similar to platforms like WordPress or Shopify. To get started, follow these steps:

Open the terminal and run the following command:

```
npx create-strapi-app@latest server
```

When prompted to choose the installation type, select "Quickstart" (recommended).

### Step 2: Signing Up in Strapi

After running the installation command, a terminal window will open with the Strapi signup page. Sign up using email to create an account.

### Step 3: Navigating the Dashboard

Upon signing up, you will be redirected to the Strapi dashboard. Here, you'll find several options on the left-hand side. The two main sections we'll be using are:

- **Content Manager**: This section allows you to create new entries for each collection type.
- **Media Library**: You can store images or videos in this section.

### Step 4: Creating a Content Type

To create a new content type, follow these steps:

1. Click on "Content Type Builder" in the dashboard.
2. Navigate to "Collection Types" and select "Create a new Collection Type".
3. Enter a display name for the collection type. For example, let's use "Item" as the display name.
4. Add fields to the collection type:
   - Create a new Text Field named "name".
   - Create a new Short Text Field named "shortDescription".
   - Create a new Rich Text Field named "longDescription".
   - Create a new Number Field named "price" (decimal).
   - Create a new Media Field named "image" (single media).
   - Create a new Enumeration Field named "category" with the options "newArrivals", "bestSellers", and "topRated" (used for our filtering system).
5. Save the collection type.

### Step 5: Adding Images to the Media Library

Go to the Media Library in the dashboard and upload any related images you want to use for your project. For this particular project, I used images from unsplash.com.

### Step 6: Adding Items
In the admin dashboard, go to "Content Manager" and click on "Create New Entry" to add new items to the website. Fill in the related fields as "name","shortDescription", "longDescription","price","image"(choose the images from the Media library) and "category".

Save the item then if everything is set click on "publish"

I used Chatgpt for "shortDescription" and "longDescription".
