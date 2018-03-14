# Adding Navbar To Your Project

    To add a basic navbar in your site use the line below. It will add an empty navbar element.

    ```html
    <nav class="navbar navbar-expand-lg fixed-top ">
    </nav>
    ```

## Adding Branding To Your Navbar

    Bootstrap provides class navbar-brand which can be used to add branding. This will add an element to top left corner of your site with a link to #.

    ```html
           <a class="navbar-brand" href="#">My Site</a>
    ```
    
## Adding Other Links On Navbar

    1. To add other links on the Navbar. You will need to create a container for them. To do so use the div like below

    ```html
        <div class="navbar navbar-collapse">
        </div>
    ```

    Also add the following css to nvabar-collapse so it will be aligned to the right.

    ```css
        .navbar-collapse{
            justify-content: flex-end;
        }
    ```

    2. Add an unordered list for adding links

    ```html
    <ul class="navbar-nav mr-4">
    </ul>
    ```

    3. Add items inside the list

        Add li elements with clas nav-item and hyperlink elements with class nav-link

    ```html
        <li class="nav-item">
            <a class="nav-link" href="1">Link 1</a>
        </li>
    ```

### Final Code

    ```html
    <nav class="navbar navbar-expand-lg fixed-top ">
        <a class="navbar-brand" href="#">My Site</a>
        <div class="navbar-collapse">
            <ul class="navbar-nav mr-4">  
                <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                </li>
            </ul>
        </div>
    </nav>
    ```