{
  "title": "Multicore Test Generator/Validator",
  "date": "2015-01-01",
  "description": "A project developed and engineered for generating arm based multicore tests for Freescale's LayerScape family of SoCs",
  "fact": "",
  "featured":true,
  "weight": 6
}

This project was engineered as part of my employment at Freescale Semiconductor. We had an old infrastructure for generating PowerPc based multi-core tests which we was tied to a proprietary test case generator tool developed by some other team. When ARM64 based SoCs started coming as part of Freescale's transition plan, we had a problem. The proprietary test case generator development was lagging behind and we had to move ahead fast to port the old PowerPC based tests to the new ARM based SOCs. This led to from-scratch implementation of an ARM64 test case generator using gnu cross-compiler for ARM at it's backend and python based tests as the frontend. Along with the test generator, I also developed a prototype implementation for a validation infrastructure for loading these tests, running them and verifying the results on actual silicon in the lab.
