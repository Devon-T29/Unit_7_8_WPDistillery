# # Project 7/8 - WordPress Pentesting

Time spent: 6 hours

## Pentesting Report

### 1. Media Post XSS Vulnerability
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 3.13
    - Fixed in version: 3.14
  - [ ] Steps to recreate: First go to the media portion of wp, next insert some javascript that forces a prompt, then utilize the view/preview attachment page link to the rightmost section of the screen.
  
### 2. Comment Post XSS Vulnerability 
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 3.13
    - Fixed in version: 3.14
  - [ ] Steps to recreate: First go to the comment portion of wp, next insert some javascript that forces a prompt, hit post and a alert should occur.

    



## Assets

An image file was downloaded from the internet to test a possible breach.

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [Peek].

## Notes

This class has been highly utilizing burp, more vm web browsers examples should be shown.

## License

    Copyright [2021] [Isaiah White-Booth]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
