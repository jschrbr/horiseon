# HoriSEOn
This is a website focused on promoting the benefits of adopting search engine optimisation techniques within existing business-based websites. This implemntation promises to increase visibility between businesses and customers, through more effective leads and widely accessible content.

## Why optimise
Effective Leads - data collection - targeting behaviours or leads
Accessible content - voice computing -  searching - marketing 

## Who benefits?

* everyone
* businesses
* customers
* people with impairments
* future proof
* new revenue streams

## The Challenge
This site was initially made without Accessability and SEO in mind. The excercise was to optomise, while learning the concepts of accessability and search engine optimisation. 

### User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
### Acceptance Criteria
* Use of semantic HTML elements
* HTML elements follow a logical structure independent of styling and positioning
* Image element with accessible alt attributes
* Heading attributes fall in sequential order
* A concise & descriptive title.

### Employing semantic HTML elements and consolodating the CSS
Ensure that all links are functioning correctly and 
clean up the CSS to make it more efficient, 

#### Optomised code
##### HTML
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
##### CSS
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
