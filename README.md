# Thunderstorm-Analyzer

ABSTRACT:
---------

Every moment our bodies are penetrated by cosmic rays. Those are tiny little particles which are coming from the rest of the universe and they can affect air and ground communication as well as airplane navigation.
It was observed that during thunderstorms number of this particles increases.
We know that those excess number of particles are not coming from space, because they occur only during atmospheric events so they should be generated inside the thundercloud.

Scientists at Alikhanyan National Science Laboratory (Yerevan Physics Institute) came up with a theory which explains why this is happening and the goal of this project is to test it and create a system which will analyze atmospheric properties like electric field, number of electrons, neutrons, muons and gamma rays taken from public weather server of Yerevan Physics Institute and study their temporal correlation to detect the cases of additional particle creation in a process called Thunderstorm Ground Enhancement (TGE).

Theory
------

It was long known that there are big charge concentrations in thunderclouds because of static electricity generated when super-cooled water droplets are colliding with ice crystals because of which charge constantly builds up until lightning will not happen between any areas of thundercloud or between cloud and ground or the thundercloud will not disperse. This can be observed by measuring overall electric field near earth surface. Usually the electric field near ground is at the levels of 0.2 - 0.5 kV/m during bright weather, but during thunderstorms that number can rise with absolute magnitude to the levels of 60 - 70 kV/m.
When lightning happens charge distribution within the cloud changes and simultaneously the magnitude of overall electric field near ground falls down immediately. 
The idea is that there is a big potential difference between earth surface and thundercloud thus charged particles from cosmic rays can accelerate during propagation through the air and clouds with strong atmospheric electric fields. We know that when charged particles moves with acceleration they emits radiation (gamma rays) thus loosing energy and eventually stopping, but if external electric field will be higher of some certain value the energy gain from external field will be higher than energy looses from gamma ray emissions, those electrons will continue to propagate with positive acceleration and kicking off electrons from air atoms. Those kicked off atoms on their turn will continue to do the exact same thing, like in chain reaction. Eventually in the end it will end up with particle shower when only couple of electrons will generate great amount of electrons and gamma rays.
This process is called a Thunderstorm Ground Enhancement (TGE).
The TGE events are characterized by following 7 criteria:

 - Large fluxes of electrons and gamma rays with duration  around 10 minutes;
 - Increase in neutron number;
 - Microsecond electron bursts with around 50ms duration;
 - Increase of high energy muon level;
 - Large, usually negative, near-surface electric field, rising sometimes from deep negative to near zero positive values. Usually field is at the level of -10 - -30 kV/m;
 - Decrease of the cloud-ground lightnings and increase of intra-cloud lightnings.
 - Increase of relative humidity above 80% and decrease of air temperature below 5 - 6* Celsius.

The system should analyze all the data and look for this kind of events and notify us upon their occurring.

Public Weather Server which includes cosmic ray detectors, electric field meters and lightning detectors: http://www.crd.yerphi.am/adei
