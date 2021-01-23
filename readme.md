Data
Air Travel Consumer Report Period From June 2003 to October 2020

Airline Delay Causes Database:
Airport delay statistics (Bureau of Transportation Statistics): Dataset obtained from: Dataset link

carrier information:
carrier: Airline code.
carrier_name: Airline name.
airport: Airport code.
airport_name: Airport name.
Airport statistics:
arr_flights: Number of flights which arrived at the airport.
arr_del15: Number of flights delayed (>= 15minutes late).
carrier_ct: Number of flights delayed due to air carrier (e.g. maintenance or crew problems, aircraft cleaning, baggage loading, fueling, etc.).
weather_ct: Number of flights delayed due to weather.
nas_ct: Number of flights delayed due to National Aviation System (e.g. non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control).
security_ct: Number of flights delayed due to security (e.g. evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas).
late_aircraft_ct: Number of flights delayed due to a previous flight using the same aircraft being late.
arr_cancelled: Number of cancelled flights.
arr_diverted: Number of diverted flights.
arr_delay: Total time (minutes) of delayed flights.
carrier_delay: Total time (minutes) of delayed flights due to air carrier.
weather_delay: Total time (minutes) of delayed flights due to weather.
nas_delay: Total time (minutes) of delayed flights due to National Aviation System.
security_delay: Total time (minutes) of delayed flights due to security.
late_aircraft_delay: Total time (minutes) of delayed flights due to a previous flight using the same aircraft being late.
Airport Database:
Dataset obtained from: Aviation Support Tables

airports.csv describes the locations of US airports, with the fields:

AirportID: An identification number assigned by US DOT to identify a unique airport. Use this field for airport analysis across a range of years because an airport can change its airport code and airport codes can be reused.
Airport: A three character alpha-numeric code issued by the U.S. Department of Transportation which is the official designation of the airport. The airport code is not always unique to a specific airport because airport codes can change or can be reused
AirportName:Airport Name.
AirportCityName: Airport City Name with either U.S. State or Country"EX: NY =New York"
AirportCountryName: Country Name for the Physical Location of the Airport (USA).
AirportStateName: State Name for the Physical Location of the Airport.
Latitude: Decimal degrees, usually to six significant digits. Negative is South, positive is North.
Longitude: Decimal degrees, usually to six significant digits. Negative is West, positive is East.
This majority of this data comes from the FAA, but a few extra airports (mainly military bases and US protectorates) were collected from other web sources by Ryan Hafen and Hadley Wickham.

Slide Type
Skip
Types of Delay
Carrier Delay
Carrier delay is within the control of the air carrier. Examples of occurrences that may determine carrier delay are: aircraft cleaning, aircraft damage, awaiting the arrival of connecting passengers or crew, baggage, bird strike, cargo loading, catering, computer, outage-carrier equipment, crew legality (pilot or attendant rest), damage by hazardous goods, engineering inspection, fueling, handling disabled passengers, late crew, lavatory servicing, maintenance, oversales, potable water servicing, removal of unruly passenger, slow boarding or seating, stowing carry-on baggage, weight and balance delays.

Late Arrival Delay
Arrival delay at an airport due to the late arrival of the same aircraft at a previous airport. The ripple effect of an earlier delay at downstream airports is referred to as delay propagation.

NAS Delay
Delay that is within the control of the National Airspace System (NAS) may include: non-extreme weather conditions, airport operations, heavy traffic volume, air traffic control, etc. Delays that occur after Actual Gate Out are usually attributed to the NAS and are also reported through OPSNET.

Security Delay
Security delay is caused by evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas.

Weather Delay Weather delay is caused by extreme or hazardous weather conditions that are forecasted or manifest themselves on point of departure, enroute, or on point of arrival.

OPSNET Delay Cause
Delays to Instrument Flight Rules (IFR) traffic of 15 minutes or more, experienced by individual flights, which result from the ATC system detaining an aircraft at the gate, short of the runway, on the runway, on a taxiway, and/or in a holding configuration anywhere en route.

Such delays include delays due to weather conditions at airports and en route (Weather), FAA and non-FAA equipment malfunctions (Equipment), the volume of traffic at an airport (Volume), reduction to runway capacity (Runway), and other factors (Others). Flight delays of less than 15 minutes are not reported in OPSNET. ASPM reports the most dominant OPSNET delay cause for any flight with an ASQP Reported NAS Delay.

flight information
Diverted Flight
A diverted flight is one that has been routed from its original arrival destination to a new, typically temporary, arrival destination. The leg of the flight that is routed back to the original arrival destination is called the recovery leg.

When you are viewing flight information for a diverted flight, you will see the diversion leg. The recovery leg will be displayed only if available.