## Search for users and Display their Details
#### HTML Structure

- section.wiki
  - div.container
    - img
    - h3(text)
    - form.form
      - input.form-input type='text'
      - button.submit-btn (search) type='submit'
  - div.results
    - div.articles
      - a
        - h4
        - p (lorem20)

#### API DOCS

- [github apis to get user details](https://api.github.com/users/)
- [github apis to get user's repository details](https://api.github.com/users/repos)

- ready to go url's

#### Initial Setup

- select form, input, results
- listen for submit events
- if empty value, display default
- create getUser()
- pass valid input value into the createUserCard()


#### Render Results

- iterate over the list
- pull out name, bio, followers, following, no. of repos
- setup a card and put the above data into div with id 'user-info'
- pull out repo details such as name, url based on their stars
- put the repo details based on lexicographical order into div with id 'repos'  
- set the result and display it