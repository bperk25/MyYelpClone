# SimpleYelp

## Bryant Perkins

**SimpleYelp** displays a list of search results from the Yelp API and displays the results in a scrollable list. 

Time spent: **9** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [x] Ability to query the Yelp API to get results from a search query
* [x] The search results are displayed in a RecyclerView

The following **extensions** are implemented:

* [x] You can search the data base by default of California (would update based on user location)
* [X] Add a location using a comma to separate tags

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='SimpleYelp_BryantPerkins.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Notes

My biggest challenge with this project was troubleshooting the onChange listener for the editText query.
I ended up using an editText and button to signal an new query to the Yelp API in the correct format.
While I would have liked to use a SearchView, I could not get it to work so I hardcoded this search feature
just using those two separate elements.

## License

    Copyright 2021 **Bryant Perkins**

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
