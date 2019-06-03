import React, { Component } from 'react';
import { Nav , NavDropdown, Navbar } from "react-bootstrap";

class Links extends Component{
    render(){
        return(
            <div>
                <Nav className="navbar navbar-expand-sm navbar-dark bg-info mb">
                    <div className="container-fluid">
                        <div className="navbar-header">
                            <Navbar.Brand>
                                <img src={require('../logo.jpeg')} width="150" height="60" className="d-inline-block align-top" alt=""/>
                            </Navbar.Brand>
                        </div>
                        <Nav.Item>
                            <Nav.Link href="/home"><h5 className="text-dark">Home</h5></Nav.Link>
                        </Nav.Item>
                        <div className="col-md-1"></div>
                        <NavDropdown title="Project" className="text-dark" id="basic-nav-dropdown">
                            <div className="dropright">
                                <button className="btn" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    Add Project
                                </button> 
                                <div className="dropdown-menu">
                                    <NavDropdown.Item href="/add_project">Add New</NavDropdown.Item >
                                    <NavDropdown.Divider />
                                    <NavDropdown.Item href="/project_list">Project List</NavDropdown.Item >
                                    <NavDropdown.Divider />
                                    <NavDropdown.Item href="/">Something </NavDropdown.Item >
                                    <NavDropdown.Divider />
                                    <NavDropdown.Item href="/">Separated link</NavDropdown.Item >
                                </div>
                            </div>
                            <NavDropdown.Divider />
                            <div className="dropright">
                                <button className="btn" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    Project List
                                </button> 
                                <div className="dropdown-menu">
                                    <NavDropdown.Item href="/add_project">Add New</NavDropdown.Item >
                                    <NavDropdown.Divider />
                                    <NavDropdown.Item href="/project_list">Project List</NavDropdown.Item >
                                    <NavDropdown.Divider />
                                    <NavDropdown.Item href="/">Something </NavDropdown.Item >
                                    <NavDropdown.Divider />
                                    <NavDropdown.Item href="/">Separated link</NavDropdown.Item >
                                </div>
                            </div>
                        </NavDropdown>
                        <div className="col-md-4"></div>

                    </div>
                </Nav>
            </div> 
        );
    }
}

export default Links;
