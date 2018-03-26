# gregslist

A project that displays and creates cars, jobs, and houses.
These objects must follow a particular model as follows in order to successfully create new objects of a type.

## Cars
All cars must look like: 

var car = {
  make: "Ford",
  model: "Aspire",
  imgUrl: "https://placehold.it/200x200",
  year: 1985,
  price: 200,
  description: "This one is optional"
}

## Jobs
All jobs look like:

var car = {
  company: "Microsoft",
  jobTitle: "Cortana AI Learning Coordinator",
  hours: 73,
  rate: 159,
  description: "This one is optional"
}

## Houses
All houses look like:

var houses = {
  bedrooms: 4,
  bathrooms: 1,
  imgUrl: "https://placehold.it/200x200",
  levels: 2,
  year: 2015,
  price: 200000,
  description: "This one is optional"
}

Build an interface that allows users to view, add and remove postings. Postings should be organized by type.
