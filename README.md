# BeResponsive
BeResponsive is my simple work from scratch to show that a beautiful responsive website can be made with HTML and CSS. 
<!DOCTYPE HTML>
<html>

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Creating a Responsive Web Design</title>
    <link rel="stylesheet" type="text/css" media="screen" href="css/screen.css">
    <link rel="stylesheet" type="text/css" media="print" href="css/print.css">

</head>

<body>

    <div id="page">

        <header>
            <a class="logo" title="Responsive production ready design" href="http://jancychristy.com"><span>Everyday Things</span></a>
            <div class="hero">
                <h1>Add Your Hello Message Here</h1>
                <a class="btn" title="Get advice from top designers" href="#">Click this <span>button to find more details</span> </a>

            </div>
        </header>

        <section class="main">

            <aside>
                <div class="content trending">
                    <h3><a href="#">What&apos;s trending</a></h3>
                    <p>Lorem ipsum dolor sit amet, consect etuer adipiscing elit. <a href="http://codifydesign.com">Morbi commodo</a>, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis.</p>
                </div>
            </aside>

            <aside>
                <div class="content find-it">
                    <h3><a href="#">All About Us</a></h3>
                    <p>Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Nullam sit amet enim. Lorem ipsum dolor sit amet, consect.</p>
                </div>
            </aside>

            <aside>
                <div class="content tools">
                    <h3><a href="#">Tools and Services</a></h3>
                    <p>Nullam sit amet enim. Lorem ipsum dolor sit amet, consect etuer adipiscing elit. Morbi commodo, ipsum sed pharetra gravida, orci rhoncus neque, id pulvinar odio.</p>
                </div>
            </aside>

        </section>

        <section class="atmosphere">
            <article>
                <h2>Creating a modern responsive design</h2>
                <p>Morbi commodo, ipsum sed pharetra gravida, orci magna rhoncus neque, id pulvinar odio lorem non turpis. Lorem ipsum dolor sit amet etuer adipiscing elit. Pulvinar odio lorem non turpis. Nullam sit amet enim lorem.</p>
                <a class="btn" title="Creating a modern responsive design" href="#">Learn more</a>
            </article>
        </section>


        <section class="how-to">
            <aside>
                <div class="content">
                    <img alt="Choosing the proper seating" src="images/photo_seating.jpg">
                    <h4>How-To: Select 1</h4>
                    <p>Consectetuer adipiscing elit. Morbi commodo ipsum sed gravida orci magna rhoncus pulvinar odio lorem.</p>
                    <a title="Learn how to choose the proper seating." href="http://codifydesign.com">Learn more</a>
                </div>
            </aside>

            <aside>
                <div class="content">
                    <img alt="Choosing the proper lighting" src="images/photo_lighting.jpg">
                    <h4>How-To: Select 2</h4>
                    <p>Morbi commodo, ipsum sed pharetra gravida magna rhoncus neque id pulvinar odio lorem non turpis nullam sit amet.</p>
                    <a title="Learn how to choose the proper lighting." href="http://codifydesign.com">Learn more</a>
                </div>
            </aside>

            <blockquote>
                <p class="quote">Lorem ipsum dolor sit amet conse ctetuer adipiscing elit. Morbi comod sed dolor sit amet consect adipiscing elit.</p>
                <p class="credit"> <strong>Author Name</strong> <br><em>Business Title</em><br>Company</p>
            </blockquote>

        </section>


        <nav>
            <ul>
                <li>
                    <a title="About Us" href="#" aria-haspopup="true">About Us</a>
                    <ul>
                        <li>
                            <a title="Sublink 1" href="#">Sublink 1</a>
                        </li>
                        <li>
                            <a title="Sublink 2" href="#">Sublink 2</a>
                        </li>
                        <li>
                            <a title="Sublink 3" href="#" aria-haspopup="true">Sublink 3</a>

                            <ul>
                                <li>
                                    <a title=" Sub Sublink 1" href="#">Sub Sublink 1</a>
                                </li>
                                <li>
                                    <a title=" Sub Sublink 2" href="#">Sub Sublink 2</a>
                                </li>

                            </ul>
                        </li>
                    </ul>
                </li>
                <li>
                    <a title="Design Corner" href="#" aria-haspopup="true">Design Corner</a>
                    <ul>
                        <li>
                            <a title="Sublink 1" href="#">Sublink 1</a>
                        </li>
                        <li>
                            <a title="Sublink 2" href="#" aria-haspopup="true">Sublink 2</a>
                            <ul>
                                <li>
                                    <a title=" Sub Sublink 1" href="#">Sub Sublink 1</a>
                                </li>
                                <li>
                                    <a title=" Sub Sublink 2" href="#">Sub Sublink 2</a>
                                </li>

                            </ul>
                        </li>

                    </ul>
                </li>
                <li>
                    <a title="Products" href="#" aria-haspopup="true">Products</a>
                    <ul>
                        <li>
                            <a title="Sublink 1" href="#">Sublink 1</a>
                        </li>
                        <li>
                            <a title="Sublink 2" href="#">Sublink 2</a>
                        </li>

                    </ul>
                </li>

                <li>

                    <a title="Contact Us" href="#">Contact Us</a>

                </li>

            </ul>
        </nav>

        <footer>
            &copy; Everyday Things
            <div class="content">
                <a title="Privacy Policy" href="#">Privacy Policy</a>
                <a title="Terms of Services" href="#">Terms of Service</a>
            </div>
        </footer>

    </div>

    <!-- react component  -->

    <div id="like_button_container"></div>
    <script src="https://unpkg.com/react@16/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js" crossorigin></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    <!-- Load our React component. -->
    <script src="like_button.js"></script>
</body>

</html>
