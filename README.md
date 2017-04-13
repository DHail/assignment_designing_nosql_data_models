Dave Hail
Will Whitworth

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


Intermediate
1.
    {
      year = {
        date(string rep of date) = {
          seats = [1,2,3,...60],    //each as 60 for total number of seats in restaurant
          reservations = {
            time_of_reservation(string rep of time) = [name, phone_no, no_of_guests]
          }
        }
      }
    }

3.
{
  student_id,
  fname,
  lname,
  email,
  password,
  semesters = {
    semester = {
      classes = [{name: grade}, {name: grade}]
    }
  }
}


Advanced

1.
    products = [
      {
        id,
        name,
        description,
        price = [{datetime, price}],
        qty,
        department = []
      }
    ]

    orders = [
      {
        id,
        order_date,
        ship_date,
        received,
        customer_id,
        order_items = [],
        total
      }
    ]

2.

    {
      id,
      fname,
      lname,
      email,
      password,
      activity = [
        {
          date,
          activity
        }
      ]
      friends = [
        {
          id,
          last_contact
        }
      ],
    }
