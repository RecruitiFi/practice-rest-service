# Project Description

RecruitiFi allows organizations to create job listings, known as a JobCast: a similiar name might be a job post.  A JobCast stores all information related to the job listing and is tied to an organization with an individual who created it.  We want to provide a service by which applications can both retreive JobCast information and persist it to a data store.  These applications will be internal to our company at first and eventually  be made public.  For this endeavor, do not focus on authentication and authorization as it is not part of the deliverable.


## Goal

- Implement a service using Rails, Sinatra, or Rack
- Define a restful interface for JobCasts
- Isolate JobCasts: rely on unique identifiers versus existing domain objects


## Expectations

- Use Bundler for gem dependencies
- Adhere to a REST interface
- Test the interface (below) using RSpec
- Define a non-file based data store
- Share your project on github for review
- Be prepared to discuss your decisions/trade-offs
- Spend no more than 4 hours on the challenge


## Domain

##### Organization

**attributes**:
name, url

##### Individual

**attributes**:
first name, last name, email, password

##### JobCast

**attributes**:
title, description, compensation_range, skills, city, state, postal_code, country_code


## Interface

Transport: JSON

Methods: List, Retrieve, Create, Update, and Destroy


## Testing

As mentioned, write all tests with the Rspec framework. A testing harness should execute using the following command.

    $ rspec spec


## Dependencies

These links are provided as a helper to find information. These are not the
only sources, so look for more if they do not give a full explanation.

[Bundler](http://bundler.io/)

[RSpec](http://rspec.info/)

[Rails](http://rubyonrails.org/)

[Sinata](http://www.sinatrarb.com/)

[Rack](http://rack.github.io/)
