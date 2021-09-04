# Amazon_Hackathon_ML

Amazon catalog consists of billions of products that belong to thousands of browse nodes (each browse node represents a collection of items for sale). Browse nodes are used to help customer navigate through our website and classify products to product type groups. Hence, it is important to predict the node assignment at the time of listing of the product or when the browse node information is absent.

As part of this hackathon, we used product metadata to classify products into browse nodes. We had access to product title, description, bullet points etc. and labels for ~3MM products to train and test your submissions. Note that there is some noise in the data (real world data looks like this!!)


## Full Train/Test dataset details:
Key column – PRODUCT_ID

Input features – TITLE, DESCRIPTION, BULLET_POINTS, BRAND

Target column – BROWSE_NODE_ID

Train dataset size – 2,903,024

Number of classes in Train – 9,919

Overall Test dataset size – 110,775
