# assignment_designing_nosql_data_models
I'll have one data model hold the SQL please


1.
{
  id = auto,
  fname = "Frank",
  lname = "Franken",
  email = "some@thing.com",
  password = ''*****',
  friends = [ids]
  profile = {
    location = {
      vis,
      address,
      zip,
      city,
      state,
      country
      },
    phone_number = {
      vis,
      number
      },
    gender= {
      vis,
      gender
      },
    birthday = {
      vis,
      birthday
      },
    description = "",
    },
}

2.
seats = number;






table = {
  available,
  number_of_seats,
  reservations = [
    {
      phone_number,
      name,
      time
    }
  ]
}

open_table = {}

  group_tables_seats[

  ]
