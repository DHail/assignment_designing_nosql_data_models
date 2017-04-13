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

4.
products = {
  id,
  name,
  description,
  price = [{datetime: price}],
  qty
}

orders = [
  {
    id,
    customer_id,
    order_items = [],
    
  }
]

receipts






