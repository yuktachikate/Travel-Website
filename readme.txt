About our website

    I have created a travel website, which has 4 webpages 
        Home
        About 
        Explore
        Contact Us 

    The assignment includes CSS Grid layout/Flexbox and SASS/SCSS Features.
    Implemented SASS Features are the following-
    - Variables : Made 2 Variables/ Custom Properties , i.e. color and color-group. They are storing the color value. 
    - Nesting : I have use nesting throughout the application. For eg, in style.scss flie, .nav{
                                                                                 add__logo{
                                                                                       ...
                                                                                  }
                                                                          }
    - Interpolation : I have used interpolation in style.scss. For eg, $con: "contact";

                                                                                .#{$con} {
                                                                                    }

    - Placeholder Selectors : I have used Placeholder Selectors in style.scss for adding the styling discribed in the selector. For eg, %remove_margin_and_padding {
                                                                                                                                                                    margin: 0;
                                                                                                                                                                    padding: 0;
                               Also I have used the placeholder selector in the following line, body {
 
                                                                                                         @extend %remove_margin_and_padding;
                                                                                                    } 
                                                    
    - Mixins : I have used mixins to describe the justified content for the element. For eg, @mixin justify-content-center {
                                                                                                                display: flex;
                                                                                                                justify-content: center;
                                                                                                                }

                                                                                            @mixin justify-content-space-between {
                                                                                                                display: flex;
                                                                                                                justify-content: space-between;
                                                                                                                            }   
    - Functions : I have created another file _function.scss to store the function lighten-color, which was used to lighten the color for the navigation links on hover. For get, @function lighten-color($color) {
                                                                                                                                                                                    @return lighten($color, 10);
                                                                                                                                                                                    }

 I divided the styling logic into multiple files. One file containt the variable for the site theme and other file consisted of functions which were used to make the site interactive and the main styling logic was in style.scss 


    I have created a navbar which takes the user to all the 4 pages mentioned above
    Navbar used <a> to link all the webpages with each other
    
    Home: 
        Home is the main page of the application

    About:
        In about I have entered dummy content to describe my travel website
    
    Explore:
        I have added a explore button in home page, which takes us to explore webpage, which contains the details about the various places.
        Using a <table> tag, I have depicted the top 10 places to visit

    Contact Us: 
        In Contact Us page, form tag and input tags are used to create a contact form





            