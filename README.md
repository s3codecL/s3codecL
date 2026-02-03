# Table of Contents
- [Introduction](#introduction)
- [Team & Collaboration](#team--collaboration)
- [Let's Connect](#lets-connect)
- [GitHub Analytics](#github-analytics)
- [Certifications](#certifications)
- [Professional Experience](#professional-experience)
- [Technical Stack](#technical-stack)
- [Aegis HUB](#aegis-hub)

# Introduction
Welcome to the s3codecL repository, where we work on various projects related to DevOps.

# Team & Collaboration
<div style="overflow: hidden;">
    <span style="float: left; margin-right: 10px;">👤 @s3codecL - Role: Semi senior DevOps</span>
    <span id="typing-animation" style="font-family: monospace;"></span>
</div>
<script>
const typingAnimation = document.getElementById('typing-animation');
const roles = ['Cloud Engineer', 'Automation Specialist', 'Infrastructure Architect'];
let i = 0;

function typeRole() {
    typingAnimation.innerHTML = ''; // Clear previous text
    let role = roles[i];
    let j = 0;

    function typingEffect() {
        if (j < role.length) {
            typingAnimation.innerHTML += role[j];
            j++;
            setTimeout(typingEffect, 100);
        } else {
            i = (i + 1) % roles.length;
            setTimeout(() => {
                roleBackspaceEffect(role);
            }, 1000);
        }
    }

    typingEffect();
}

function roleBackspaceEffect(role) {
    let j = role.length;

    function backspaceEffect() {
        if (j > 0) {
            typingAnimation.innerHTML = role.substring(0, j - 1);
            j--;
            setTimeout(backspaceEffect, 100);
        } else {
            typeRole();
        }
    }

    backspaceEffect();
}

typeRole();
</script>

# Let's Connect
Connect with us on our platforms:
<div style="display: flex; justify-content: space-around;">
    <a href="#" style="font-size: 24px;">💼 LinkedIn</a>
    <a href="#" style="font-size: 24px;">🐦 Twitter</a>
    <a href="#" style="font-size: 24px;">🌐 Website</a>
</div>

# GitHub Analytics
| Repository | Link |
|------------|------|
| s3codecL   | [View Repo](https://github.com/s3codecL) |

# Certifications
We have a collection of over 70+ certifications:
- AWS Certified Solutions Architect
- Microsoft Certified: Azure Developer Associate
- ...

# Professional Experience
Detailed professional experience of the team members.

# Technical Stack
| Technology | Badge |
|------------|-------|
| AWS        | ![AWS Badge](https://img.shields.io/badge/amazon-aws-ff9900) |
| Azure      | ![Azure Badge](https://img.shields.io/badge/microsoft-azure-0078d4) |

# Aegis HUB
Featured project highlighting our work with Aegis HUB.