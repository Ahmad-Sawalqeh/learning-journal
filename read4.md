# Structure web pages with HTML

##  Process & Design

> Every website should be designed for the target audience—not just for yourself or the site owner.

> Target AuDience:
1. Individuals:
- What is the age range of your target audience?
- What kind of device do they use to access the web?
- How often do they use the web?

1. Companies:
- Will visitors be using the site for themselves or for someone else?
- What is the size of the company or relevant department?

> Invent some fictional visitors from your typical target audience. They will become your friends. They can influence design decisions from color palettes to level of detail in descriptions.

> You need to consider why your visitors are coming. While some people will simply chance across your website, most will visit for a specific reason. so you need to work out what information they need in order to achieve their goals quickly and effectively.

## HTML Layout

> HTML layout elements:
- `<header>` At the Top of every page.
- `<main>` At the center of every page.
- `<footer>` At the bottom of every page.
- `<nav>` element is used to contain the major navigational blocks on the site such as the primary site navigation.
- `<section>` element groups related content together, and typically each section would have its own heading.
- `<artical>` element acts as a container for any section of a page that could stand alone and potentially be syndicated.

> Examples for HTML:

```

!DOCTYPE html>
 <html>
  <head>
    <title>HTML5 Layout</title>
  </head>
  <body>
    <header>
        <h1>Yoko's Kitchen</h1>
        <nav>
                <ul>
                    <li><a href="" class="current">home</a></li>
                    <li><a href="">classes</a></li>
                    <li><a href="">catering</a></li>
                    <li><a href="">about</a></li>
                    <li><a href="">contact</a></li>
                </ul>
        </nav>
   </header>
   <section class="courses">
       <article>
            <figure>
                    <img src="images/bok-choi.jpg" alt="Bok Choi" />
                    <figcaption>Bok Choi</figcaption>
            </figure>
            <hgroup>
                    <h2>Japanese Vegetarian</h2>
                    <h3>Five week course in London</h3>
            </hgroup>
            <p>
                A five week introduction to traditional Japanese vegetarian meals, teaching you a selection of rice and noodle dishes.
            </p>
        </article>
        <article>
            <figure>
                <img src="images/teriyaki.jpg" alt="Teriyaki sauce" />
                <figcaption>Teriyaki Sauce</figcaption>
            </figure>
            <hgroup>
                <h2>Sauces Masterclass</h2>
                <h3>One day workshop</h3>
            </hgroup>
            <p>
                An intensive one-day course looking at how to create the most delicious  auces for use in a range of Japanese cookery.
            </p>
        </article>
        <footer>
            &copy; 2011 Yoko's Kitchen
        </footer>
    </section
  </body>
</html>

```

## Extra Markup

> At this point, we have covered the main tags that fit nicely into groups and sections. Since the web was first created, there have been several different versions of HTML:

1. XML.
1. XHTML 1.0.
1. HTML 4.
1. HTML 5.

> comment on HTML:

`<!-- add your comment here -->`


> id attribut:

`<p id="my_id_name"></p>`

> iframes:

`<iframe  width="450"  height="350"  src="google map link"></iframe>`