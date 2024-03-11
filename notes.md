Accessibility Tips to keep in mind:

If you're going to use the placeholder statement right on the html, you have to be aware that this is not great in terms of acessibility, since it's not readable in the voice over tool.
To help and fix that, you can label its input as the same name you'll have on placeholder.
Afterwards, with CSS, you are able to manage a way to make it not visible on screen, but readable for those who need. 

After that, you can use the functionality/class sr only (screen read only) and adjust the CSS in a way that it's readable for the Voice Over Tool, but not visible to our non-machine eyes. 

In case I need to understand what happened to the part that left the td inside tbody 

    <td class="user">
                    <img src="https://github.com/diego3g.png" alt="Imagem de Diego Fernandes">
                    <a href="https://github.com/diego3g" target="_blank">
                        <p>Diego Fernandes</p>
                        <span>diego3g</span>
                    </a>
                </td>
                <td class="repositories">
                    48
                </td>
                <td class="followers">22503</td>
                <td>
                    <button class="remove">&times;</button>
                </td>

