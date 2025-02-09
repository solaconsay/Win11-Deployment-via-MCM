# Win11-Deployment-via-MCM

## Overview

This project provides a step-by-step guide for deploying Windows 11 to client machines using Microsoft Configuration Manager (MCM) (formerly SCCM). The deployment leverages an answer file (unattend.xml) to automate installation settings while the task sequence ensures seamless domain joining and system configuration.

This project is part of my Enterprise Automation course in my final semester at Nova Scotia Community College (NSCC) as an IT Systems Management and Security student. **Please read the Guide.md for the detailed steps.**

## Features

- Automated Windows 11 installation using an SCCM task sequence

- Pre-configured system settings via an answer file

- Seamless Active Directory integration

- Deployment via Software Center or PXE boot

- Configuration Manager client installation for monitoring

## Prerequisites

- Microsoft Configuration Manager (SCCM) environment

- Windows 11 ISO

- Distribution Points (DPs) for OS and boot images

- Proper network and domain configurations

- Administrative privileges on SCCM and Active Directory

## Notes

- Ensure that Windows 11 hardware requirements are met.

- Verify network and domain connectivity before deployment.

- Test the deployment on a small group of machines before full rollout.