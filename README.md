# Biomek Automated Methods

Repository of the London Biofoundry's automated methods on the Biomek workcell composer of:

* Biomek i7 - Liquid handling robot
* Echo 550 - Accounting liquid handling robot
* ClariostarPlus - Plate reader 
* Precise - Robotic Arm
* Liconic STX - Automated shaker incubator

## Structure

### Development stages 

Corresponds to the split of the folders in which methods are stored. 

#### Under Development

The automated method is being developed. It hasn't been validated yet. 

#### Validated 

The automated method went through the validation process successfully. It is safe to be used. 

#### Runs 

Backup of the method version used to run samples through the method. 

### Naming convention 

#### Method#_Name_v# (e.g Method14_MediaCulturesDoE_v1)

Used for methods under development or validated. 

* Method#: internal ID 
* Name: biological process name 
* v#: version number 

#### Method#_Name_v#_Date_Operator (e.g Method14_MediaCulturesDoE_v1_06092022_Keltoum) 

Used for automated runs. 

* Method#: internal ID 
* Name: biological process name 
* v#: version number 
* Date: date of the run
* Operator: name of the person who performed the run 

## License

[London Biofoundry](https://www.londonbiofoundry.org/)
