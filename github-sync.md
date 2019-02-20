/*
Title: GitHub Sync 
Description: Learn how to sync Glo with GitHub Issues.
Sort: 4
*/

Syncing your GitHub Issues in Glo lets you break issues out into columns and visualize them in Glo.

Type your code here

<img src='/img/documentation/glo/github-sync/sync-issue.gif' class='img-bordered img-responsive center'>

### What gets synced from GitHub?
* GitHub Issues
* Assignees
* Description
* Comments
* Labels


***

<a id="connect-to-github"></a>

## Connect to GitHub

The <button class='button button--success button--ui button--nolink'>Connect to GitHub</span></button> button is available from the bottom of the left Boards panel in Glo.  

<img src='/img/documentation/glo/github-sync/boards-github.png' srcset='/img/documentation/glo/github-sync/boards-github@2x.png 2x' class='img-bordered img-responsive center'>

You can also connect to GitHub from the Integrations section of the User Options menu. 

<img src='/img/documentation/glo/github-sync/connect-github.gif' class='img-bordered img-responsive center'>

Click the <button class='button button--success button--ui button--nolink'>Connect to Github</span></button> button, login to GitHub, and authorize Glo.

<img src='/img/documentation/glo/github-sync/authorize-glo.png' srcset='/img/documentation/glo/github-sync/authorize-glo@2x.png 2x' class='img-bordered img-responsive center'>

You GitHub account should now be connected to Glo!

<img src='/img/documentation/glo/github-sync/successful-connect.png' srcset='/img/documentation/glo/github-sync/successful-connect@2x.png 2x' class='img-bordered img-responsive center'>

<a id="create-a-synced-board"></a>

***

## Create a Synced Board

Open the Boards panel and click on the <button class='button button--success button--ui button--nolink'>Create a synced board</span></button> button.

<img src='/img/documentation/glo/github-sync/create-sync-board.png' srcset='/img/documentation/glo/github-sync/create-sync-board@2x.png 2x' class='img-bordered img-responsive center'>

Search for the GitHub repo issue board you wish to sync.

<img src='/img/documentation/glo/github-sync/search-repo.png' srcset='/img/documentation/glo/github-sync/search-repo@2x.png 2x' class='img-bordered img-responsive center'>

<div class='callout callout--warning'>
  <p>**Note:** You must be an administrator for the GitHub repo to create the initial synced board.  The repo name will be grayed out with a lock icon if you don't have administrator permissions on that repo.</p>
</div>

<div class='callout callout--basic'>
  <p>**Heads up!** Glo has a max syncing limit of 1000 issues. If you have repos with 1000+ issues you wish to sync, consider first archiving older issues in GitHub.</p>
</div>

Click the <button class='button button--success button--ui button--nolink'>Yes, create synced board</span></button> button to confirm that you wish to sync this board with Glo.

<img src='/img/documentation/glo/github-sync/confirm-sync.png' srcset='/img/documentation/glo/github-sync/confirm-sync@2x.png 2x' class='img-bordered img-responsive center'>

GitHub synced boards will be indicated by the GitHub logo to the left of the board name.  

<img src='/img/documentation/glo/github-sync/github-icon.png' srcset='/img/documentation/glo/github-sync/github-icon@2x.png 2x' class='img-bordered img-responsive center'>

<div class='callout callout--danger'>
  <p>**Important:** Glo's GitHub Sync relies on a repo webhook created during the sync set up.  Please do not modify or remove this webhook as this will cause the GitHub sync to fail.</p>
</div>

<a id="managing-synced-boards"></a>

***

## Managing Synced Boards

When you first sync a board, you will start out with just one column in Glo. However from here you can _create more columns_ and build out the workflow for your issues. 

<img src='/img/documentation/glo/github-sync/Createboard.gif' class='img-bordered img-responsive center'>

From here, new issues added to GitHub will now sync to Glo.

<img src='/img/documentation/glo/github-sync/sync-issue.gif' class='img-bordered img-responsive center'>

Conversely, new cards added to Glo will also be synced to GitHub.  You may need to refresh GitHub to see the new issue.

<img src='/img/documentation/glo/github-sync/sync-to-github.gif' class='img-bordered img-responsive center'>

Type the GitHub issue number in the search field to quickly find corresponding card.

<img src='/img/documentation/glo/github-sync/filter-by-issue.png' srcset='/img/documentation/glo/github-sync/filter-by-issue@2x.png 2x' class='img-bordered img-responsive center'>

Also, if you ever want to jump to the GitHub issue from Glo, click on this icon to access the link:

<img src='/img/documentation/glo/github-sync/View-on-Github.png' srcset='/img/documentation/glo/github-sync/View-on-Github@2x.png 2x' class='img-bordered img-responsive center'>

