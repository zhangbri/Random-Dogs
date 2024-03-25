# AND101 Project 6 - CYOAPI Part 2: RecyclerView Edition

Submitted by: **Brian Zhang**

Time spent: **2** hours spent in total

## Summary

**Dog Generator** is an android app that fetches and displays random dog images from the Dog CEO API in a scrollable list. Users can view a variety of dog images and click on each image to receive a notification indicating the position of the clicked dog image in the list.

If I had to describe this project in three (3) emojis, they would be: **🐕‍🦺🐾🐶**

## Application Features

The following REQUIRED features are completed:

- [X] Make an API call to an API of your choice using AsyncHTTPClient
- [X] Implement a RecyclerView to display a list of entries from the API
- [X] Display at least three (3) pieces of data for each RecyclerView item

The following STRETCH features are implemented:

- [X] Add a UI element for the user to interact with API further
- [X] Show a `Toast` or `Snackbar` when an item is clicked
- [X] Add item dividers with `DividerItemDecoration`

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<p align="center">
  <img src="randomDogs.gif" title="Random Dogs" alt="Random Dogs GIF" />
</p>

GIF created with **ScreenToGif**

<!-- Recommended tools:
- [Kap](https://getkap.co/) for macOS
- [ScreenToGif](https://www.screentogif.com/) for Windows
- [peek](https://github.com/phw/peek) for Linux. -->

## Notes

- **Dynamic Dog Image Fetching:** Enables spontaneous discovery of various dog breeds through random image generation.
- **Efficient List Display:** Utilizes RecyclerView for smooth scrolling and optimized view handling of dog images.
- **Asynchronous Image Retrieval:** Implements AsyncHttpClient for non-blocking, responsive data fetching.
- **Glide Integration:** Facilitates smooth image loading and display within the list using Glide.
- **Interactive Elements:** Adds click listeners on list items, enhancing interactivity with Toast feedback.
- **Visual Layout Enhancement:** Employs LinearLayoutManager and DividerItemDecoration for organized and visually appealing list presentation.
- **Utilization of Kotlin Features:** Demonstrates modern Kotlin practices with lateinit and mutable lists for dynamic data management.

## License

Copyright **2024** **Brian Zhang**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
