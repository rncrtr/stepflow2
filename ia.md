#StepFlow Information Architecture

## accounts
 - ID
 - email
 - password
 - colorSchemeID

## flows
 - ID
 - title = text
 - steps = Array
 - authorId = int
 - created = date
 - modified = date
 - public = bool
 - URL = text
 - tags = Array

## steps
  - ID
  - parentID = ID
  - flowID = ID
  - text = text
  - content = text
  - img = url
  - video = text
  - ord = int

## tags
  - ID
  - userId = ID
  - taxonomy = ID
  - term

## colorSchemes
  - ID
  - Name
  - colors = Array

## taxonomies
  - ID
  - name

## terms
  - ID
  - term