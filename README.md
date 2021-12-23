# Kickstarter Data Service (API). Search projects by a custom filter.

Unofficial Kickstarter API.

`/projects` - Search for projects using filters.

*Available params:*
- `category_id` - Retrieve projects by category.
- `sort` - 
- `page` - 
- `state` - 
- `pledged` - < $1,000, $1,000 to $10,000, $10,000 to $100,000, $100,000 to $1,000,000, > $1,000,000
- `goal` - < $1,000, $1,000 to $10,000, $10,000 to $100,000, $100,000 to $1,000,000, > $1,000,000
- `raised` - < 75% raised, 75% to 100% raised, > 100% raised
- `term` - 3D, Food Trucks, Dogs, …
- `location_id` - If you need to filter projects by location

You can try it here: https://rapidapi.com/apimaker/api/kstarter

Working on new endpoints:
`profile` - data about creator
`createdBy` - all projects created by the given creator
