# Third-Party References / Attribution Notes

Use this file as a compatibility-reference sheet inside your commercial package.
This is not legal advice.

## 1) SSC-32 / SSC-32U / BotBoarduino / Phoenix lineage
These names are third-party trademarks / product names and should only be used in nominative form
to explain compatibility, for example:
- "Compatible with the SSC-32 command set"
- "Configured for BotBoarduino-style Arduino deployment"
- "Derived from / inspired by Phoenix-style multi-legged controller code"

Suggested public wording:
> This digital package is an independent CinoGear-branded project. Any mention of SSC-32, SSC-32U,
> BotBoarduino, Lynxmotion, Phoenix, PlayStation / PS2, or PS2X is for compatibility reference only.
> No affiliation or endorsement is claimed.

Reference URLs:
- https://www.lynxmotion.com/ses-v1-modular-robot-system/
- https://www.lynxmotion.com/ses-v1-legged-robot/

## 2) PS2X Arduino library
The included PS2X library folder is third-party code and should remain clearly separated from your
CinoGear-branded source. Keep original author credits and GPL notice intact.

Reference URLs:
- https://www.billporter.info/2010/06/05/playstation-2-controller-arduino-library-v1-0/
- https://www.gnu.org/licenses/gpl-3.0.html

## 3) Uploaded source observations
- The PS2X library explicitly declares GNU GPL v3 or later in its original header/readme.
- The Phoenix-derived controller files in the uploaded archive show attribution comments, but no fully
  explicit standalone license block was visible in the inspected source headers.
- Because of that, you should manually review upstream permission/licensing before commercial sale.
