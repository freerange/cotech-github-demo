__This repo is deprecated: [The idea of moving to a static website was proposed and rejected in Loomio](https://www.loomio.org/d/FnHRkxCO)__

Screenshots showing how to add a new cooperative to the Jekyll version of the [CoTech website][jekyll-website].

## Creating a pull request

This sequence of screenshots shows [new-cooperative][] (a GitHub user) creating a pull request using only the GitHub user interface. Note that the user is not a member of the [cotech][] GitHub organisation so a [fork][] of the repository is automatically created. The pull request (now closed) can still be seen [here][pull-request].

### Open `_coops` directory

![01](images/new-cooperative-screenshot-01.png)

### Create new file representing new coop

![02](images/new-cooperative-screenshot-02.png)

### Name the markdown file after coop name

![03](images/new-cooperative-screenshot-03.png)

### Add content to file

![04](images/new-cooperative-screenshot-04.png)

### Preview new content

![05](images/new-cooperative-screenshot-05.png)

### Propose new coop file

![06](images/new-cooperative-screenshot-06.png)

### Navigate back to the root of project

![07](images/new-cooperative-screenshot-07.png)

### Navigate to new branch

![08](images/new-cooperative-screenshot-08.png)

### Open `images` directory

![09](images/new-cooperative-screenshot-09.png)

### Open `coops` sub-directory

![10](images/new-cooperative-screenshot-10.png)

### Prepare to upload new coop logo

![11](images/new-cooperative-screenshot-11.png)

### Upload new coop logo

![12](images/new-cooperative-screenshot-12.png)

### See new coop logo has been uploaded

![13](images/new-cooperative-screenshot-13.png)

### Add new logo to the branch

![14](images/new-cooperative-screenshot-14.png)

### Prepare to open pull request based on branch

![15](images/new-cooperative-screenshot-15.png)

### Explain purpose of pull request

![16](images/new-cooperative-screenshot-16.png)

### Create pull request including new coop page & logo

![17](images/new-cooperative-screenshot-17.png)

## Merging a pull request

This sequence of screenshots shows [floehopper][] who is a member of the [cotech][] GitHub organisation merging the pull request submitted by [new-cooperative][]. This causes the website to be re-generated and as long as there are no errors, the new version is deployed.

### Merge pull request

![01](images/floehopper-screenshot-01.png)

### Confirm merge

![02](images/floehopper-screenshot-02.png)

### See pull request has been merged

![03](images/floehopper-screenshot-03.png)

## Viewing changes on public website

These screenshots show that the new cooperative now appears in all the relevant places on the [public version of the website][jekyll-website].

### See new coop in list of members on home page

![01](images/public-screenshot-01.png)

### See new coop on map of members on home page

![02](images/public-screenshot-02.png)

### See new coop page (part 1)

![03](images/public-screenshot-03.png)

### See new coop page (part 2)

![04](images/public-screenshot-04.png)

### See new coop appears on "Consultancy" service page

![05](images/public-screenshot-05.png)

### See new coop appears on "Apache" technology page

![06](images/public-screenshot-06.png)

[new-cooperative]: https://github.com/new-cooperative
[cotech]: https://github.com/cotech
[floehopper]: https://github.com/floehopper
[pull-request]: https://github.com/cotech/statically-generated-website/pull/2
[fork]: https://github.com/new-cooperative/statically-generated-website
[jekyll-website]: https://cotech.github.io/statically-generated-website/
