Kelsie Lloyd

1. I would probably go with 2. Option 1 also sounds legitimate, but I imagine it would be best to test code out for yourself before trying to actually push it. Perhaps even with tests implemented in Github actions, this would prevent additional work if it worked on both your individual tests and the Github tests. Additionally, it might even cover some potential pitfalls that may not be covered by the Github tests.

2. No. Based on my understanding, that's more geared for unit testing. E2E testing involves more so testing from a user's perspective, so I would presume individual functions would be less relevant in this scope.

3. Navigation checks on the status of the page right after it loads. Snapshot checks the page in its current state, whatever given period that may be. The former is ideal for checking performance while the latter is ideal for checking accessibility issues.

4. Correctly size the images, give the HTML element a lang attribute (for accessibility purposes), add a viewport meta tag to make the site easier and more accessible to read on mobile devices
