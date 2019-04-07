<p align="center">
<a href="https://cdn4.iconfinder.com/data/icons/ikooni-outline-seo-web/128/seo-12-512.png"></a>
<br><br>
           
</p>
Descriptions
<ul>
<li> In the "Shipping Requests" tab of the application, all tasks should show in the backlog swimlane.</li>
<li> There should be 3 swimlanes.</li>
<li> When a user drags a card up, down or into another swimlane, it reorders the card and stays there. (frontend only)</li>
<li> When a card changes swimlane, it should change color </li>
</ul>

## Available Scripts

In the project directory, you can run:

### `npm start`

this runs the app in the development mode.
<br>Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

We have loaded some clients data in Board.js.
Each client is an object of
interface Client {
  id: number,
  name: string,
  description: string,
  status: 'backlog' | 'in-progress' | 'complete,
}

Visit Dragula repository on github for more information
[https://github.com/bevacqua/dragula](https://github.com/bevacqua/dragula)
