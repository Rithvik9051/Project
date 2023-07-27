<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="SectioMyProjectsHome">
        <div class="my-project-home-page">
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/software-developer-img.png" class="software-developer-image" />
            <h1 class="my-projects-heading">My projects</h1>
            <p class="my-projects-description">
                These are a few of my static website projects that I have developed
                using HTML, CSS and Bootstrap
            </p>
            <div class="d-flex flex-row justify-content-center">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/advanced-technologies-img.png" class="my-project-image" onclick="display('sectionAdvancedTechnologies')" />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/advanced-technologies-img.png" class="my-project-image" onclick="display('sectionAdvancedTechnologies')" />
            </div>
            <div class="d-flex flex-row justify-content-center">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/food-img.png" class="my-project-image" onclick="display('sectionFoodOrder')" />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/news-paper-img.png" class="my-project-image" onclick="display('SectionNews')" />
            </div>
        </div>
    </div>
    <div id="sectionAdvancedTechnologies">
        <div class="Advanced-Technologies-bg-container d-flex flex-column justify-content-center">
            <div class="advanced-technologies-card">
                <h1 class="advanced-technologies-title">Advanced Technologies</h1>
                <p class="advanced-technologies-description">
                    Machinery and equipment developed from the application of scientific
                    knowledge.
                </p>
                <button class="advanced-technologies-leaarn-more-button">
                    Learn more
                </button>
                <button class="btn btn-primary" onclick="display('SectioMyProjectsHome')">
                    Back
                </button>
            </div>
        </div>
    </div>
    <div id="sectionDiwali">
        <div class="diwali-top-section">
            <h1 class="diwali-top-section-heading">
                Celebrate Diwali with your freinds
            </h1>
        </div>
        <div class="diwali-bottom-section">
            <div class="d-flex flex-row justify-content-center">
                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-img.png" class="diwali-card-item" />
                    <h1 class="diwali-card-name">Diwali Air Ballon</h1>
                    <p class="diwali-card-price">Rs 369</p>
                </div>
                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-img.png" class="diwali-card-item" />
                    <h1 class="diwali-card-item">Diwali-lamp</h1>
                    <p class="diwali-card-price">Rs 50</p>
                </div>
            </div>
            <div class="d-flex flex-row justify-content-center">
                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-img.png" class="diwali-card-item" />
                    <h1 class="diwali-card-name">Sparkles</h1>
                    <p class="diwali-card-price">Rs 150</p>
                </div>
                <div class="diwali-card-item">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/news-paper-img.png" class="diwali-card-item">
                    />
                    <h1 class="diwali-card-price">Fire Cracker</h1>
                    <p class="diwali-card-price">Rs 560</p>
                </div>
            </div>
            <div class="d-flex flex-row justify-content-center">
                <button class="btn btn-primary" onclick="display('SectioMyProjectsHome')">
                    Back
                </button>
            </div>
        </div>
    </div>
    <div id="sectionFoodOrder">
        <div class="food-order-bg-container d-flex flex-column justify-content-end">
            <div class="order-card">
                <h1 class="order-card-heading">Happy Meals</h1>
                <p class="order-card-paragraph">
                    Discover the best foods over the 1,000 restaurants
                </p>
                <button class="order-card-button">Book Now </button>
                <button class="btn btn-pimary" onclick="display('SectioMyProjectsHome')">
                    Back
                </button>
            </div>
        </div>
    </div>
    <div id="SectionNews">
        <div class="news-bg-contianer d-flex flex-column justify-content-end">
            <div class="news-card">
                <p class="news-category">News of the Day</p>
                <h1 class="news-title">
                    All education institute is Assam to reopen from November 2
                </h1>
                <p class="news-title">
                    Uttar pradesh GAUTAM BUDDH NAGAR recorder 107 new covid-19 cases
                    on saturday , pushing the district's infection tally t 15,803,
                    offically data showed. The number of active cases came down further
                    to 1,3084 from 1,477 on Friday and 1,523 on thursday, accordig to
                    the data released by the Up Health Department for a 24-hour period.
                </p>
                <button class="news-button">Read more </button>
                <button class="btn btn-priary" onclick="display('SectioMyProjectsHome')">
                    back
                </button>
            </div>
        </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>
