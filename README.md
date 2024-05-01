##CONCEPT
    This is a sample fashion retail site.
    It will be built using JavaScript, React, Python, and a PostgreSQL db.


##Front-end FEATURES
    Nav bar/footer that persist throughout site. Nav bar and links to:
        - Homepage (from the logo)
        - Collection Pages (with parent dropdown)
        - Care Instructions
        - FAQ Page
        - About Page
        - Cart (icon)
        - Socials (icons)
    Homepage will feature:
        - Hero section with background image. Foreground will be the company name.
        - Gallery section with images of items
            # These will navigate to the detail page for the item on click
    Collection Pages
        - Will have a header section for the title
        - Will have a gallery section for the featured items
        - Each item will display it's name and price with options to view details or add to cart
    Item Detail Pages
        - Will have an item description
        - An image carousel of the item
        - a section with dimensions, details and pricing with an add to cart button
        - A logistics section with curated FAQs, return policy, etc.
    Care Instructions
        - General care instructions for each type of fabric
    FAQ Page
        - List frequently asked questions and their answers
    About Page
        - The origin story
    Cart
        - List of all items that were added and their prices
        - The current bill summary
        - A suggested additions section at the bottom

##Back-end Features
    Postgres DB
    Migrations 
        -Structure DB tables
    Queries 
        - Create pydantic models for db queries
    Routers 
        - Create RESTful urls to call methods on the pydantic models
    Tests
        - Conduct unit testing
NOTES
    I may eventually add user authentication and inventory tracking functionality.
    This is an initial concept and subject to change.
