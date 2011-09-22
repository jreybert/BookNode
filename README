BookNode
========

This script allows you to easily manage reservations on a shared computer. Users can add a reservation, delete an old one, see all pending reservations etc...

For now, nothing is blocked during a reservation, users are just notified that a reservation is running.

Commands
--------

Booking system usage:
Options:
  --book,   -b  : book idkonn for a given time
    --mail, -m  : automatically send a mail to the mailing list
                  when booking or canceling a book
  --cancel, -c  : cancel one of your booking
  --list,   -l  : list the future bookings
  --help,   -h  : display this message

.:: Book ::.
  book-node -b [-m] tonight [email_address]
    or
  book-node -b [-m] begin_date end_date [email_address]
      begin_date: dd-mm-yyyy-hh
      end_date  : dd-mm-yyyy-hh
         or     : Nh (add N hours)
         or     : night
         or     : we (week end)
  NB: you must provide your mail address the first time

.:: Cancel ::.
  book-node -c [-m] book_id
  NB: you can find your book_id with the list



