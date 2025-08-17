<div align="center">

# Prompting with Sign Parameters for Low-resource Sign Language Instruction Generation

</div>

<p align="center">
  <strong>Md Tariquzzaman</strong>
    ·
    <strong>Md Farhan Ishmam</strong>
    ·
    <strong>Saiyma Sittul Muna</strong>
      ·
     <strong>Md Kamrul Hasan</strong>
     ·
   <strong>Hasan Mahmud</strong>
</p>

<div align="center">

[![arXiv](https://img.shields.io/badge/CV4A11y@ICCV_2025-68448b?style=flat&logoColor=white&color=68448b&labelColor=FFFFFF&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNjAiIGhlaWdodD0iMTYwIj48cGF0aCBmaWxsPSIjNzJBMENFIiBkPSJNMTA4IDI3aDUydjE1aC0zM3YxOGgxOGwuMDYzIDcuNDM4LjAyNyAyLjM0NWMuMDA3IDEuNzQtLjA0IDMuNDc4LS4wOSA1LjIxNy0xIDEtMSAxLTQuODE2IDEuMDk4YTcwNSA3MDUgMCAwIDEtNC43NDYtLjAzNUwxMjcgNzZ2MzNoLTE5bC0xLTQzYy03LjMyMyAxNS42OTEtMTQuNTggMzEuMzk3LTIxLjU5NiA0Ny4yMjctMi45NzIgNi42OC02LjA2MSAxMy4yNy05LjQwNCAxOS43NzMtMy0xLTMtMS00LjI5NC0zLjAxOGwtMS4zMDYtMi42OTEtMS40OTktMy4wNDktMS42LTMuMzM2LTEuNjc5LTMuNDM4YTIzNjYgMjM2NiAwIDAgMS00LjQxNC05LjExNWMtMS40NjItMy4wMjYtMi45MzYtNi4wNDctNC40MS05LjA2OEE0MjExIDQyMTEgMCAwIDEgNDcgNzlsLTEuMzYtMi44MjdxLTEuNzQzLTMuNjMtMy40NzItNy4yNjdsLTEuMDAxLTIuMDg2QzM5IDYyLjIzMyAzOSA2Mi4yMzMgMzkgNjBoMTljMTYgMzAuMjMgMTYgMzAuMjMgMTYgMzNoMmwxLjE0NS0zLjcxNWMyLjA1Mi02LjE1OCA0Ljc5OC0xMS45NzMgNy41NDMtMTcuODQ3LjUxLTEuMTA1IDEuMDIyLTIuMjA5IDEuNTQ4LTMuMzQ2UTg4LjExMyA2NC4wNDMgOTAgNjBoMTh6Ii8+PHBhdGggZmlsbD0iIzZCOUJDQyIgZD0iTTYwLjYyNSAzMy4yNSA2MyAzNWMtMS41MzIgMy41ODQtMy42NjcgNi4wMjktNi4zNzUgOC44MTNsLTIuMzM2IDIuNDU3QzUyIDQ4IDUyIDQ4IDQ5Ljg4NyA0Ny44MjhMNDggNDdjLTYuNzA0LTIuNTMzLTEyLjQyNi0yLjg2LTE5LjA3OC0uMTAyLTUuMzAxIDMuMDM5LTguNjA3IDguMjE2LTEwLjQ1IDEzLjk0MkMxNi43MzkgNjguNzY4IDE3Ljg5IDc1Ljk5IDIyIDgzYzMuODQ2IDQuNjA4IDguMDEzIDcuMTE3IDE0IDggNC4wMjYtLjE0NyA4LjAwMS0uNTE0IDEyLTFxMS43NTcgMy40MzUgMy41IDYuODc1bDEuMDEyIDEuOTczQzU1IDEwMy43NzMgNTUgMTAzLjc3MyA1NSAxMDZjLTguNjMyIDQuNDA4LTE5LjA5OCA0LjM5Ni0yOC40MTggMi4xOTEtMTAuNDMyLTMuOS0xNy45MDEtMTEuMDk2LTIzLjQyNi0yMC42MzZDLTEuNzE1IDc2Ljc5LTIuMjYyIDYxLjUgMS44NzUgNTAuMzc1YzUuNTI5LTEwLjg3MSAxNC4zOTEtMTguOTk3IDI1LjkzOC0yMy4wMDQgMTEuODkzLTIuMDE4IDIyLjY1Mi0uNjkxIDMyLjgxMiA1Ljg3OSIvPjxwYXRoIGZpbGw9IiM2Mjk1Q0EiIGQ9Ik0xMDkgMjhoNTB2MTNoLTMzdjIwaDE5djE0aC0xOXYzM2gtMTd6Ii8+PHBhdGggZmlsbD0iIzk1QjhEQSIgZD0iTTM5IDYwaDE5djNsLTMtMWMtMi4zOTUtLjA3LTQuNzkyLS4wODQtNy4xODctLjA2MmwtMy44NTYuMDI3TDQxIDYybC0xIDJ6Ii8+PC9zdmc+&style=flat&logoWidth=15)](https://cv4a11y.github.io/)
[![arXiv](https://img.shields.io/badge/Code-tariquzzamanf/SPIP-blue?logo=GitHub)](https://github.com/tariquzzamanf/SPIP)
</div>

---

**tldr:** We introduce BdSLIG, a low-resource sign language instruction generation dataset on Bengali and Sign Parameter-Infused (SPI) prompting that integrates the visual cues used to describe the sign language into the vision-language prompt.

## Sign Parameters
The following sign parameters are provided to the vision-language prompt for SPI prompting:
1. **Handshape**: The morphological configuration, e.g., raised, extended, pointed, bent, spread, twisted, of the fingers and palms.  
2. **Movement Type**: The trajectory or action of the hands, e.g., static, circular, squeezing, grabbing, rotating, pulling.  
3. **Location**: The placement of the hands while producing the sign, e.g., near head, forehead, eye, ear, nose, mouth, chest, shoulder.  
4. **Palm Orientation**: The direction the palm is facing relative to the signer's body, e.g., inward, outward, upward, downward, left, right.  
5. **Spatial Interaction**: The role of one or both hands in the sign's spatial scheme, e.g., right-hand active, left-hand active, both-hands symmetric, both-hands asymmetric.  
6. **Temporal Dynamics**: The temporal pattern of the movement onset, duration, and repetition, e.g., sustained hold, repeated oscillation, single tap, repeated tapping.  
7. **Facial Cues**: Facial expressions, e.g., neutral, brows-raised, brows-furrowed, mouth-open, mouth-closed, lip-pursed, that can disambiguate the sign language.  
