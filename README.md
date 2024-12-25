# Melbourne

<p align="center">
    <img width="128" height="128" src="/resources/logo_128.png?raw=true">
</p>

*Melbourne* is a program that generates scoreboard images for online music song competitions. As a former online competition host, I have found that creating scoreboard images when presenting results is a rather time-consuming activity and repetitive activity. *Melbourne* was consequently born out of a desire to mostly automate this process and make it easier for me to host competitions.

In many ways, this program has been a labor of love for me; this upcoming summer 2020 will mark the eighth anniversary of my starting development of this program and I have definitely learned a lot these past few years developing and improving this application.

## History

As you might have noticed from the title of this document, this is the fifth major version of Melbourne. While under development since 2012, the first major release of Melbourne occurred on escforum.net in January 2015 (as I had used it privately before then). The second major release occurred in April 2015. Since then, Melbourne has been improved quite dramatically, going from a SVG image generator to a PNG image generator, with a more robust architecture and user-interface. 

The third and fourth major versions of Melbourne were released in mid-2016 and early-2017 respectively to a small subset of users. These versions never left beta status as there remained several major limitations in these versions that prevented them from being publicly released.

For clarity, this most recent major rewrite of the program compared to previous edition necessitated the increase in version number to `5.0.0`.

## Gallery

### Screenshots
![Screenshot of Melbourne](/resources/screenshot.png)

### Sample Scoreboard Image
![Example scoreboard generated by Melbourne](/resources/1988.png)*Example scoreboard generated by Melbourne showing the final results of the Eurovision Song Contest 1988.*

# Running 

```bash
uv run python -m uvicorn melbourne.api.api:app
```