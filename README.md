# elec1005-studysphere
ELEC1005 FINAL PROJECT 
#IF YOU CAN EDIT SAY HI AND SAY UR NAME (JANA)
#HI! (Ansley Wang)
#HI! (Sarah Aiko)
#HI! (Zeheng Li)
#HI! (Houda)
hey guys so i dont thinks theres much left other than the report its self 
maybe the testcases too 
also if there is any code you can sned here that would be great 
there is link ellie will send join if you can.


https://uni-sydney.zoom.us/j/7404358862?pwd=VjFhZXh1cEFNYVFnQ0NBSUpwZHIvQT09
Password: 049819
That should be the zoom link if anybody wants to join and work on the assignment. Hopefully we can get it all done by today

powerapp:
https://make.powerapps.com/e/a42f41f8-c15d-eedf-9bf8-d84097b321c8/canvas/?action=edit&app-id=%2Fproviders%2FMicrosoft.PowerApps%2Fapps%2F93e71799-555c-4e29-9fc4-3b9ef67df270

sharepoint:
https://unisydneyedu.sharepoint.com/:u:/r/sites/elec1005-group21/SitePages/CollabHome.aspx?csf=1&web=1&share=ETOlnRB0OrRClBGb6JLyc_AB7Dr4SOrC7OgLFW2eWXLBow&e=qUrtf6

Grade Calculator:
  code for Button1:
  UpdateContext({gpa: 
      (
          If(Value(TextInput2.Text) >= 1, Value(TextInput3.Text) * Value(TextInput3_1.Text), 0) + 
          If(Value(TextInput2.Text) >= 2, Value(TextInput3_2.Text) * Value(TextInput3_3.Text), 0) + 
          If(Value(TextInput2.Text) >= 3, Value(TextInput3_4.Text) * Value(TextInput3_5.Text), 0) + 
          If(Value(TextInput2.Text) >= 4, Value(TextInput3_6.Text) * Value(TextInput3_7.Text), 0) + 
          If(Value(TextInput2.Text) >= 5, Value(TextInput3_8.Text) * Value(TextInput3_9.Text), 0)
      ) / 
      (
          If(Value(TextInput2.Text) >= 1, Value(TextInput3_1.Text), 0) + 
          If(Value(TextInput2.Text) >= 2, Value(TextInput3_3.Text), 0) + 
          If(Value(TextInput2.Text) >= 3, Value(TextInput3_5.Text), 0) + 
          If(Value(TextInput2.Text) >= 4, Value(TextInput3_7.Text), 0) + 
          If(Value(TextInput2.Text) >= 5, Value(TextInput3_9.Text), 0)
      )
  });

  code for Button1_1:
  Reset(TextInput2);
  Reset(TextInput3);
  Reset(TextInput3_1);
  Reset(TextInput3_2);
  Reset(TextInput3_3);
  Reset(TextInput3_4);
  Reset(TextInput3_5);
  Reset(TextInput3_6);
  Reset(TextInput3_7);
  Reset(TextInput3_8);
  Reset(TextInput3_9);

  code for Label1:
  Text(gpa)

NAME, SECTION,
CODE:If(
    CountRows(Filter(SelectedDatesCollection, Date = DatePicker1.SelectedDate)) > 0,
    Remove(SelectedDatesCollection, Date = DatePicker1.SelectedDate),
    Collect(SelectedDatesCollection, {Date: DatePicker1.SelectedDate})
)

What do we have left:
powerapps:
notif
TASK M.
FORMATING DETAILS

report:
user manual 
testcases (5 to 6 each functions)
ss of testcase outcome
jira
github 
