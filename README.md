# HoriSEOn
This is a website focused on promoting the benefits of adopting search engine optimisation techniques within existing business-based websites. This implemntation promises to increase visibility between businesses and customers, through more effective leads and widely accessible content.

## Who benefits?
### Everyone!
* Businesses - Get better insights into there customers, as well as new potential revenue streams with social media marketing and voice controlled computing.
* Customers - Get increased accuracy with search results, finding exactly what they need. This also welcomes people living with impairments to your content.

## The Challenge
This site was initially made without Accessability and SEO in mind. The excercise was to optomise the site, while learning the concepts and techniques behind accessability and search engine optimisation. 

### User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
### Acceptance Criteria
###### Use of semantic HTML elements
  * The elements that were added to the code are:  
  * ```<header>, <main>, <nav>, <section>, <article>, <aside> & <footer> ```
###### HTML elements follow a logical structure independent of styling and positioning
  * The document has the following structure:
    * Head
    * Body
      * Header
      * Main
        * Section (Background)
        * Section
          * Article
        * Section
          * Aside
      * Footer
###### Image element with accessible alt attributes
  * Concise descriptions of the image were used to convey information. As well as there is an instance of the role attributebeing set to presentation. This alerts a non-visual user that the image is for decorative purposes only, with no information.
###### Heading attributes fall in sequential order
  * All heading attributes are maintained and will have a logical flow regardless of style.
###### A concise & descriptive title.
  * The chosen title was:
    * Horiseon: Search Engine Optimisation

## Employing semantic HTML elements and consolodating the CSS
### Old code
###### HTML
```html
<div class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>

        ...
        
    </div>
```
###### CSS
```css
.content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

...

.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

...

.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

...

```


### Optomised code
###### HTML
```html
        <!-- Main Content -->
        <section id="content">
            <!-- SEO Article -->
            <article id="search-engine-optimization">
                <img src="./assets/images/search-engine-optimization.jpg" class="float-left" role="img" alt="Search Engine Optimisation: Content, Headings, Mobile Compatability, Social Media, Link Building and Backlink" />
                <h2>Search Engine Optimization</h2>
                <p>
                    The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
                </p>
            </article>
            
            ...

        </section>
```
###### CSS
```css
section#content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

#content article{
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#content article img {
    max-height: 200px;
}

#content article h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
```


### Results

The following is a list of the required outputs of this project. Including the url of the deployed web application and the url of this repo, with this README :)

* Deployed App - https://jschrbr.github.io/horiseon/

* Github Repo - https://github.com/jschrbr/horiseon/
