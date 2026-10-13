# Skool-Grid

 Skool-Grid is a mobile-friendly workspace for staff to manage academic results, teaching timetables, duty rosters, announcements, calendar changes and school performance insights. Students do not need accounts in the initial concept.
 1. Product vision
    
The initial product is intended for a particular secondary boarding school. Its starting problem is practical: teachers should be able to enter and submit results from their phones rather than needing to visit a computer lab. The product then connects this academic workflow to staff timetables, duty assignments, announcements and school-calendar operations.
This is a staff-first concept. Students do not need their own accounts or dashboards in the initial version. Student records are managed by authorized school staff.

3. Users and responsibilities
Administrator
•	Create and manage staff, students, classes, subjects, sessions and terms.
•	Assign teachers to subjects and classes; assign a form teacher to each class.
•	Upload or create class timetables and staff duty rosters.
•	Manage calendar events, date changes, announcements and emergency staff meeting notices.
•	Configure grading rules and the school’s exact report-card format.
•	Review timetable warnings, incomplete results and other operational issues.

Teacher
•	See a personal daily and weekly teaching timetable.
•	See multiple subject/class assignments and form-teacher responsibilities under one account.
•	Enter, save, review and submit results on a phone.
•	See personal staff-duty assignments and relevant school events.
•	Receive schedule reminders, urgent announcements and change notifications.
•	Acknowledge important announcements when requested.

Principal
•	Monitor class, subject and term performance.
•	Track result submission and identify incomplete records.
•	Review and approve results according to the school’s chosen workflow.
•	See unresolved timetable conflicts and important operational alerts.

4. Main modules
A. Results management
•	Mobile-friendly score entry, draft saving, validation, submission and controlled correction.
•	Automatic totals and grades based on school-configured grading rules.
•	Submission tracking by class, subject, term and teacher.
•	Audit trail for score entry, edits, submission and approval.

B. School-specific printable report cards
•	The school’s existing result sheet is the reference—not a generic template.
•	After the school supplies the sample, document its layout, branding, score columns, grading formulas, remarks, signatures and print dimensions.
•	Generate individual reports and batch reports for a class, ready to print or export as PDF.
•	Allow authorized staff to configure report fields and grading rules.

C. AI-assisted timetable import
•	Admin uploads an existing timetable as an image, PDF or spreadsheet.
•	AI extracts days, periods, times, classes and subjects into a structured draft.
•	The system matches each lesson against existing teacher-subject-class assignments.
•	Admin reviews and confirms the imported timetable before publishing.
•	Each teacher gets a personal schedule and daily lesson summary.

D. Timetable conflict detection
•	Flag teachers assigned to two lessons at the same time.
•	Flag overlapping class periods, missing teacher matches, duplicate periods and invalid time ranges.
•	Show unresolved issues clearly; do not silently publish a timetable with conflicts.

E. Staff duty roster
•	Admin uploads or creates a roster with date/day, time, location and duty responsibility.
•	Teachers see their own duties and receive reminders.
•	Flag duty overlaps and conflicts with teaching periods where relevant.
•	Support substitutions and notify affected staff when assignments change.

F. Flexible school calendar
•	Record meetings, exams, holidays, deadlines and special events.
•	Allow authorized staff to reschedule, postpone, cancel or edit an event.
•	Notify affected staff when event details change and keep a change history.
•	Avoid duplicate entries and show the last synchronization time.

G. Staff announcements and emergency meetings
•	Send standard or urgent announcements to all staff, teachers, a department or selected recipients.
•	Include meeting time, venue, purpose and instructions.
•	Support acknowledgement and read-status tracking.
•	Allow scheduled messages and follow-up with staff who have not acknowledged urgent notices.

H. Academic performance analytics
•	Show class and subject averages, grade distributions and term-to-term comparisons.
•	Help leadership identify classes or subjects that may need additional support.
•	Track missing results and submission progress.
•	Keep analytics explainable; AI should not make unverified high-stakes judgments about individual students.

I. Unified teacher dashboard
•	One view for today’s lessons, staff duties, upcoming events, pending result work and announcements.
•	Show schedule changes clearly and link notifications to the relevant task.

5. Notifications and offline use
A mobile-friendly web app that can be installed on supported phones (a Progressive Web App, or PWA) is a reasonable starting direction. Browser push notifications can work on supported devices and browsers after the user grants permission.
•	Online: send push notifications for daily schedules, urgent notices, duty reminders and calendar changes.
•	Offline: previously synchronized schedules and announcements can remain viewable; local reminders may work depending on device/browser support.
•	A phone cannot receive a new internet push notification while it has no connection, and it cannot learn about a newly changed event until it reconnects.
•	Show the last-sync time and refresh information when connectivity returns.
•	For urgent messages, retain a backup such as SMS or a phone call; push delivery alone cannot guarantee that staff saw the message.

