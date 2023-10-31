# 🗓️ Create Calendar Event 

Create a calendar event using the Nylas Python SDK and Poetry.

## 📜 Introduction

The `create_calendar_event` project is a Python script that leverages the Nylas Python SDK to read and create calendar events from a Nylas calendar. It's designed to provide a straightforward way to fetch, display, and create calendar events.

## ✨ Features

- Create a calendar event given a calendar id.
- Handle Nylas API errors and edge cases.
- Integrates with Poetry for dependency management.

## ⚙️ Requirements

Before using this project, make sure you have the following prerequisites:

- Python 3.10 or higher
- Make
- Nylas API credentials (`'API_KEY'` and `'GRANT_ID'`)
- A Nylas Calendar ID

## 🔧 Using Make

You can use the `make` command for common development tasks. Here are some useful targets:

- `make venv`: Create a virtual environment.
- `make install`: Generate a `.env` file and install required dependencies.
- `make run`: Run the app using Poetry.
- `make clean`: Remove build, test, coverage, and Python artifacts.

## 🚀 Installation

1. Fork/Clone this repository to your local machine:

    ```bash
    git clone https://github.com/nylas-samples/nylas-hacktoberfest-2023.git
    cd nylas-hacktoberfest-2023/code-samples/calendar-event/python/create_calendar_event
    ```

1. Set up a virtual environment and activate it:

    ```bash
    make venv
    ```

1. Install project dependencies using Poetry:

    ```bash
    make install
    ```

1. Configure your Nylas API credentials in the `.env` file by setting your `'API_KEY'` and `'GRANT_ID'`  with your actual credentials.

## 🏁 Getting Started

After completing the installation steps, you're ready to get started:

1. Run the script to create a calendar event:

    ```bash
    make run
    ```

Read the on-screen information and copy a calendar ID to attach an event to it.

    ```bash
    *** Running the app locally... ***


    poetry run create_calendar_event
    Connected Calendars:

    Calendar ID: mahmoudddharmouchhh@gmail.com, Name: mahmoudddharmouchhh@gmail.com, Description: None
    Calendar ID: en.lb#holiday@group.v.calendar.google.com, Name: Holidays in Lebanon, Description: Holidays and Observances in Lebanon
    Calendar ID: addressbook#contacts@group.v.calendar.google.com, Name: Birthdays, Description: Displays birthdays, anniversaries, and other event dates of people in Google Contacts.
    Calendar ID: 8t4pnfu73fdiv73qreji1d2j5534dmbl@import.calendar.google.com, Name: Coursera Calendar - Mahmoud Harmouch - mahmoudddharmouchhh@gmail.com, Description: None
    Calendar ID: n1rd0h727dk44lva57qnbbeis8@group.calendar.google.com, Name: test, Description: test description
    Calendar ID: co9ko6p4qbd5fvh7i55urnvf5s@group.calendar.google.com, Name: test, Description: test description
    Calendar ID: tfnid9uts44nb1bqku4bednt14@group.calendar.google.com, Name: test-update, Description: Updated test description

    Getting events before event creation for Calendar 'test-update':

    No events found in the specified calendar.

    Event created: Event(id='c7c5ccevt3agepcccv1an05sec', grant_id='your_grant_id', calendar_id='tfnid9uts44nb1bqku4bednt14@group.calendar.google.com', busy=True, read_only=False, created_at=1698062199, updated_at=1698062199, participants=[Participant(email='oss1@wiseai.dev', status='noreply', name=None, comment=None, phone_number=None), Participant(email='oss2@wiseai.dev', status='noreply', name=None, comment=None, phone_number=None)], when=Timespan(start_time=1696107600, end_time=1729457999, start_timezone='Asia/Beirut', end_timezone='Asia/Beirut', object='timespan'), conferencing=None, object='event', description='Discuss project progress', location='Virtual', ical_uid='c7c5ccevt3agepcccv1an05sec@google.com', title='Team Meeting', html_link='https://www.google.com/calendar/event?eid=your_eid', hide_participants=False, metadata=None, creator=EmailName(email='mahmoudddharmouchhh@gmail.com', name=''), organizer=EmailName(email='tfnid9uts44nb1bqku4bednt14@group.calendar.google.com', name='test-update'), recurrence=None, reminders=Reminder(use_default=True, overrides=None), status='confirmed', visibility=None)


    Getting events after event creation for Calendar 'test-update':

    Event title: Team Meeting, start time: 2023-10-01 00:00:00, end time: 2024-10-20 23:59:59
    ```

## 📚 Documentation

This project includes Google-style documentation within the code. You can find detailed information on how the script works, its functions, and error handling in the script itself.

## 🤝 Contributing

Contributions are welcome! If you would like to improve this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure tests pass.
4. Submit a pull request with a clear description of your changes.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
