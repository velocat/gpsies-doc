### The track editor is designed for: <!-- {docsify-ignore} -->
- creating new tracks and routes, including using auto-routing;
- editing existing tracks, both posted on the site and uploaded to the editor itself from a file or by link;
- combining tracks in the form of segments;
- splitting tracks into separate segments;
- recalculation of distances and heights for both the selected and all segments of the track;
- creating and editing existing WPT waypoints (Markers);
- track processing: optimization (compression), cropping, resetting time and heights, changing direction, etc.;
- removing part of the track points by selecting the desired area;
- saving edited or created tracks both locally as a file and in storage on the site.

### The track editor has flexible settings that allow you to set: <!-- {docsify-ignore} -->
- the color and width of the line of the segment being edited and others;
- color, view and waypoint marker icon;
- display start and finish markers;
- customize editing functions, such as removing dots with a right mouse click;

To calculate heights and routing, you can enter your own [service keys](/en/) providing these services: OpenRoute, GraphHopper and Google.
Some of these services (free) are already connected in the editor, but since they have a daily quota (restriction) for use, and they are provided for all users, it may turn out that the quota has already been exhausted, and in this case you can use your own free key, which can be easily obtained on their sites.

Also, to optimize the editing of a large number of points, in order to avoid browser freezes during data processing, a restriction is set - editing is disabled in viewing mode if the number of track points on the screen is more than 500.
This value can be set in the editor settings, depending on the speed of your browser, including completely disabled.

The editor uses the browser's local storage, in which all the settings will be saved, including the track itself, which will allow you to restore the last edit at the next session.
You can disable saving settings and tracks in the browser's local storage, or download all settings as a file and apply them in another browser.