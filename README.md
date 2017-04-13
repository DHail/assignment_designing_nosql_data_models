Dave Hail
Will Whitworth

# assignment_designing_nosql_data_models
I'll have one data model hold the SQL please


    {
      id = auto,
      fname,
      lname,
      email,
      password,
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


//Intermediate


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


//Advanced


    products = [
      {
        id,
        name,
        description,
        price = [{datetime, price}],
        qty,
        department = []
      }
    ],

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
