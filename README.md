About TraX protocol
===================

What is TraX protocol?
----------------------

Tracking eXchange protocol is a simple protocol that enables easier evaluation
of computer vision tracking algorithms. The basic idea is that a tracker 
communicates with the evaluation software using a set of textual commands
over the standard input/output streams.

Reference C server implementation
---------------------------------

libtrax is a reference C implementation for the Tracking eXchange protocol that
enables researchers to quickly add support for the protocol in their C or
C++ tracker. An example is provided for the OpenCV implementation of the CamShift
tracker that shows how to approach the integration.

Matlab server implementation
----------------------------

Matlab TraX implementation is a set of Matlab functions that allow researchers 
to test their Matlab code using TraX. It is still in an eraly stage of development.

TODO list
---------

 * C API documentation
 * Protocol documentation
 * Java server implementation
 * Java client implementation
 * Tests

License
-------

trax is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

trax is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with libtrax. If not, see <http://www.gnu.org/licenses/>.

