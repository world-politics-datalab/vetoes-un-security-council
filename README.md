# List of UN Security Council Vetoes (1946-2021)

Carlos L. Yordan scraped data from the United Nations Dag Hammarskjöld Library's [webpage](https://research.un.org/en/docs/sc/quick/veto) documenting the number of vetoes issued in the Security Council from 1946-2022.

The dataset includes the following variables:

- **year**: The year the veto was issued.
- **date**: formatted as Month/Day/Year
- **month**: Month in numerical representation.
- **agenda_item**: This is the UN's description of the Security Council's agenda item. 
- **crisis_topic**: This variable provides a short description of the crisis or the topic of controversy. For example, "Admission" is used for draft resolution vetoed connected to a prospective member's request for admission to the UN. "Syria" stands for vetoes connected to the current Syrian civil war.
- **region**: It connects the "agenda_item" and "crisis_topic" to specific regions of the world. When there is no clear region, we catalogued the veto as a global.
- **USA**: This is a dummy variable, where 1 means that country vetoed the draft resolution, while 0 means that a veto was not issued.
- **France**: This is a dummy variable - 1 means that country vetoed the draft resolution, while 0 means that a veto was not issued.
- **UK**: This is a dummy variable - 1 means that country vetoed the draft resolution, while 0 means that a veto was not issued. 
- **USSR**: This is a dummy variable -  1 means that country vetoed the draft resolution, while 0 means that a veto was not issued.
- **Rusia**: This is a dummy variable - 1 means that country vetoed the draft resolution, while 0 means that a veto was not issued.
- **China**: This is a dummy variable - 1 means that country vetoed the draft resolution, while 0 means that a veto was not issued.
- **member_veto1**: This is a dummy variable - 1 means that only one country vetoed the draft resolution, while 0 means that more than one country vetoed the draft resolution.
- **member_veto2** This is a dummy variable - 1 means that only two country vetoed the draft resolution, while 0 means that only one country or three countries vetoed the draft resolution.
- **member_veto3** This is a dummy variable - 1 means that only three country vetoed the draft resolution, while 0 means that only one country or two countries vetoed the draft resolution.
- **single_veto**
- **multiple_vetoes**
