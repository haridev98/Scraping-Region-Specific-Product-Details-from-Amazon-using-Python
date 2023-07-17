<img src="https://cdn2.downdetector.com/static/uploads/logo/amazon.png" style="width:800px;height:300px;align=center;">
<br>
    
#  <font color=green>Scraping Region Specific Product Details from Amazon using Python
<br>

### Project Link: https://jovian.com/haridev5041998/scraping-region-specific-product-details-from-amazon-using-python

<p> Amazon is one of the world's largest e-commerce conglomerates, and we all know that Amazon has multiple e-commerce websites depending on the region; here is a list of Amazon e-commerce websites.</p>
    <ul>
       <li><font color=green>Amazon-Australia</li>
<li><font color=green>Amazon-Belgium</li>
<li><font color=green>Amazon-Brazil</li>
<li><font color=green>Amazon-Canada</li>
<li><font color=green>Amazon-China</li>
<li><font color=green>Amazon-Egypt</li>
<li><font color=green>Amazon-France</li>
<li><font color=green>Amazon-Germany</li>
<li><font color=green>Amazon-India</li>
<li><font color=green>Amazon-Italy</li>
<li><font color=green>Amazon-Japan</li>
<li><font color=green>Amazon-Mexico</li>
<li><font color=green>Amazon-Netherlands</li>
<li><font color=green>Amazon-Poland</li>
<li><font color=green>Amazon-Saudi Arabia</li>
<li><font color=green>Amazon-Singapore</li>
<li><font color=green>Amazon-Spain</li>
<li><font color=green>Amazon-Sweden</li>
<li><font color=green>Amazon-Turkey</li>
<li><font color=green>Amazon-UAE</li>
<li><font color=green>Amazon-UK</li>
<li><font color=green>Amazon-US</li>
    </ul>

    
                                                                    

    
    
    

<p> The goal of this project is to search for the <i><font color=#f79b34>product specified as input</i> on an Amazon website in a <i><font color=#f79b34>specific region</i> and extract data such as <i><font color=#f79b34>Product name, Product actual rate, Product discounted rate, Product rating, Product rating user count, Product image link, and Product link</i> for future data analytical purposes and export it as a comma-separated values File.</p>


### <font color=green> Here's a step-by-step outline for this project:

* Reading the input product keyword and region for the Specific region Amazon Website.

* Retrieve the product  search result Html Source code using the request python library from the region specific Amazon website.

* Parse the HTML source code using beautiful Soup python library.

* Extract the data such as Product name, Product actual rate, Product discounted rate, Product rating, Product rating user count, Product image link, and Product link from the beautiful Soup object.

* Compile the extracted information into Pandas library DataFrame.

* Export the data as comma-separated values File using Pandas library.

* Loop the same to rest of the inputs from the INPUT File.
