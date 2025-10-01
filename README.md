# play_with_earth2studio

1. The notebook play_with_earth2studio has DLWP, Cordiff over Taiwan and SFNO

2. AIFS needs more than 40 GB GPU RAM, so failed on Colab, need to test on H100

3. Fourcastnet version 3 needs more than 40 GB GPU RAM, so failed on Colab, need to test on H100

from earth2studio.models.px.aifs import AIFS

from earth2studio.models.px.aurora import Aurora

from earth2studio.models.px.base import PrognosticModel

from earth2studio.models.px.cbottle_video import CBottleVideo

from earth2studio.models.px.dlesym import DLESyM, DLESyMLatLon

from earth2studio.models.px.dlwp import DLWP

from earth2studio.models.px.dxwrapper import DiagnosticWrapper

from earth2studio.models.px.fcn import FCN

from earth2studio.models.px.fcn3 import FCN3

from earth2studio.models.px.fengwu import FengWu

from earth2studio.models.px.fuxi import FuXi

from earth2studio.models.px.graphcast_operational import GraphCastOperational

from earth2studio.models.px.graphcast_small import GraphCastSmall

from earth2studio.models.px.interpmodafno import InterpModAFNO

from earth2studio.models.px.pangu import Pangu3, Pangu6, Pangu24

from earth2studio.models.px.persistence import Persistence
from earth2studio.models.px.sfno import SFNO
from earth2studio.models.px.stormcast import StormCast
