+++
title = "Setting Up Shoko Metadata"
description = "Information on how to install Shoko Metadata on Windows"
aliases = ["/shokometadata"]
layout = "single"
[[pageNav]]
navTitle = "Plex Library Creation"
name = "Creating A Shoko Library"
id = "creating-a-shoko-library"
[[pageNav]]
navTitle = "Editing Plex Scanners"
name = "Windows"
id = "windows2"
[[pageNav]]
name = "Combining Series & Movies"
id = "combining-series--movies"
+++

## Creating A Shoko Library{.page-first-header}

With **Shoko Server** running, open **Plex** and either select **Movies** or **TV Shows**. Note if you did not do the edit mentioned on the [Shoko Metadata Install](shokometadata/install/) page to combine the libraries, you'll need to repeat these steps for the other library. 

When asked to select the **Media Folder**, browse to your anime collection. Even though Shoko will be providing the metadata, Plex still needs to know where the physical files are located. 

In the **Advanced** tab, if adding a TV library then select **Shoko Series Scanner** and **ShokoTV** or if adding a movie library then select **Shoko Series Scanner** and **ShokoMovies**. 

For users combining the library, make sure to add the library as a **TV Show** and use the **ShokoTV** agent. 

![Shoko Metadata - Inputting Server Information](/assets/images/shoko-metadata/Shoko-Metadata-Inputing-Server-Info.jpg)

You'll need to input the following information for Shoko Metadata to access your collection.

<table class="table table-bordered">
    <thead>
    <tr>
        <th>Option</th>
        <th>Description</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>Username</td>
        <td>The username for the **local account you inputted during the <strong>First Run</strong> setup in Shoko Server.</td>
    </tr>
    <tr>
        <td>Password</td>
        <td>The password for the **local account you inputted during the <strong>First Run</strong> setup in Shoko Server..</td>
    </tr>
    <tr>
        <td>Server IP</td>
        <td>The IP address for the computer Shoko Server is on. You can leave this blank unless Shoko Server is on another computer.</td>
    </tr>
<tr>
        <td>Port</td>
        <td>The port Shoko Server uses, by default it's <strong>8111</strong>.</td>
    </tr>
    </tbody>
</table>

Please note, if you set **SingleSeasonOrdering** to **True** during the install process, make sure you check the **Use single season ordering** box, otherwise it will not take effect. 

The rest of the options are self-explanatory so once you've gone through them, click the **Add Library** button. Once the library has been added, initiate a scan within Plex and wait for Plex to add your collection. 

##### Syncing Watch States

