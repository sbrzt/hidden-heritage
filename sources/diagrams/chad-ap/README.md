## Object (CHAD-AP)

![](obj_chad-ap.png)

A poster is described according to the Library Reference Model (LRM), which uses several descriptive layers for its representation. In particular:

* the Work (lrmoo:F1_Work) represents the essence or conceptualisation of the poster. Each work is associated with a title (crm:E35_Title).
* the Expression (lrmoo:F2_Expression) is the realisation of a Work, and refers to the intellectual content of the object. Both the Expression and the Work are generated through a creation event (lrmoo:F28_Expression_Creation) occurring within a specific time span (crm:E52_Time-Span). A creation event consists of a series of smaller activities (crm:E7_Activity), each conducted by one or more agents (crm:E39_Actor) identified by their own names (crm:E41_Appellation) and characterised by a specific type (crm:E55_Type) that defines, implicitly, the role assumed by the agent for that activity. For example, if the agent is identified as the photographer, the activity type is represented as photography (aat:300054225). An Expression can also be associated with one or more subjects defining its contents: a generic concept is represented with the class crm:E73_Information_Object with the type aat:300404126 (i.e. subject) explicitly specified.
* the Manifestation (lrmoo:F3_Manifestation) represents the embodiment of the poster content in a physical format. It is characterised by having a type (crm:E55_Type), which is aat:300027221 (posters).
* the Item (lrmoo:F5_Item) represents the physical, localised exemplar of the poster. It is accompanied with an identifier (crm:E42_Identifier). Also, the Item is characterised by having some dimensions (crm:E54_Dimension), each with a type (such as width or length), a unit (crm:E58_Measurement_Unit), and a value.

---

## Process (CHAD-AP)

![](proc_chad-ap.png)

On the one hand, we have the acquisition activity (crmdig:D2_Digitization_Process) involving the digitisation of a poster (crm:E24_Physical_Human-Made_Thing) to produce its digital equivalent (crmdig:D9_Data_Object). The digital poster can be associated with copyright statements or licenses (crm:E73_Information_Object with aat:300435434 as its type and documented by some authority resource online). The acquisition occurs within a time span (crm:E52_Time-Span) with defined starting and ending date times, and engages various agents, including individuals (crm:E21_Person) and institutions (crm:E74_Group) responsible for the activity. During the acquisition, a series of techniques (crm:E55_Type) can be used, such as photogrammetry (aat:300053580) or laser scanning (aat:300417743), along with tools (crmdig:D8_Digital_Device) like digital cameras (aat:300266792) and scanners (aat:300429747).

On the other hand, we have software activities, each representing a specific stage of digitisation workflow (crmdig:D10_Software_Execution). Such stage is denoted by its type (crm:E55_Type), such as processing (aat:300054636). It involves the manipulation of the digital poster (crmdig:D9_Data_Object) produced previously as input and the production of a new version of that digital poster (crmdig:D9_Data_Object) as output. The activity also occurs within a defined time span (crm:E52_Time-Span) with precise start and end date times, engages various agents (crm:E21_Person for people and crm:E74_Group for institutions), and uses software (crmdig:D14_Software) to produce an output.

People, institutions, devices and software can be identified by names (crm:E41_Appellation).
