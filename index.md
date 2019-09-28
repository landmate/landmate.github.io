---
excerpt: the open source agroecology robot
---

landmate is an attempt of an open robot platform aimed at supporting sustainable agricultural practices, such as organic farming, agroecology and permaculture. landmate targets mixed-crop cultivation, diversified landscapes, low use of external inputs, biodiversity and conservation, and use of ecosystem synergies. In contrary, most (commercial) agricultural robots target monocultural, high-input practices.

## Project aims

The landmate project is aimed at the following objectives:

* support of sustainable agricultural practices, in particular, practices referred to in agroecology, by
    * providing knowledge and recommendations for on-site agroecological measures, and
    * assisting in (hard) manual labour processes,
* collect sensor data and survey data to
    * improve the open agroecological knowledge base,
    * enhance on-site recommendations, and
    * obtain feedback.

## Status quo and next steps

A hardware platform consisting of four independently steered and driven wheels has been developed. In short, the platform currently consists of:

* a hardware frame made from woden multiplex plates and aluminium,
* four independently mounted air wheels with a diameter of 260 cm,
* four 12VDC planetary-geared motors for driving the wheels,
* four 12VDC worm-geared motors for steering the wheels,
* four Arduino Mega 2560 for reading the motors' encoder positions and generating PWM signals for the motor drivers,
* six 12V motor drivers, of which two power the four steering motors,
* a Raspberry Pi 3 for instructing the Arduinos via a serial connection and eventually collecting sensor data.

## Next steps

Current tasks involve developing the electronics and wiring the components. Following that, a software for controlling the components will be implemented.

Besides that, a project documentation should be developed and published here.

## Support and contributions

The project needs you!

landmate's aims are sophisticated, and for sure, I cannot make it become reality on my own. If you are interested in the topic or project, want to know more about it, have ideas or would even like to work on it, please contact me!

The project is currently located in Lüneburg, Germany - that is where I study. If you study nearby, e.g. at Leuphana University Lüneburg or at Technical University Hamburg, landmate may even be an opportunity for a student project or thesis.

## Contact

The project is currently maintained by Vitus Lehner. You can contact me via the following email address: vitus at landmate.org

## Thanks

Thanks to all the people supporting the project and me with technical and subject-specific guidance, and especially to [FabLab Lüneburg e.V.](https://www.fablab-lueneburg.org/) for enabling the build.
