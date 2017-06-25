DOCTYPE <html>
<html>
<body>
<h1> h1 {
display: inline;
position: relative;
letter-spacing: -5px; /* This will push it together giving us a nice 3D vibe */
color: rgba(0,0,255,0.5); /* This will give us a blue at 50% opacity */
}
h1:after {
content: “Anaglyph”;
position: absolute;
left: 8px; top: 6px; /* These are aligning it to be where we’d like relative to the last word */
color: rgba (255,0,0,0.5); /* This gives us a red at 50% opacity */
} </h1>
<p>The del element represents deleted (removed) text.</p>

<p>My favorite color is <del>blue</del> red.</p>

</body>
</html>
